# CPU Spike Incident Simulation

## Incident Description
A CPU utilization spike was intentionally triggered on the EC2 instance to test monitoring and alerting mechanisms.

## Detection
The issue was detected when the CloudWatch alarm changed to the ALARM state after CPU utilization exceeded the defined threshold.

## Root Cause
A high CPU-consuming process was manually executed on the EC2 instance during testing.

## Resolution
The process was identified and terminated, which reduced CPU utilization and restored normal operation.

## Verification
The CloudWatch alarm returned to the OK state after CPU usage normalized.

## Learning
This simulation helped in understanding incident detection, diagnosis, and resolution workflow.
