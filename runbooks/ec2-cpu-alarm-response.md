
# EC2 CPU Alarm Response Runbook

## Alert Description
This alert is triggered when EC2 CPU utilization exceeds 70% for 5 minutes.

## Detection
The issue was detected through a CloudWatch alarm monitoring CPU utilization.

## Root Cause
A high CPU process was manually triggered on the instance during incident simulation.

## Resolution Steps
- Logged into EC2 instance using SSH
- Identified the high CPU process
- Terminated the process to normalize CPU usage

## Verification
Confirmed CPU utilization returned to normal and the alarm state changed to OK.

## Preventive Actions
- Monitor application processes
- Review instance sizing if high CPU usage is frequent
