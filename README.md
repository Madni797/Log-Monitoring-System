# Log Monitoring and Analysis

## Objective

The objective of this project is to monitor and analyze Linux system logs using the journalctl utility to detect system events, errors, and security-related activities.

## Tools Used

- Kali Linux
- VMware Workstation
- Linux Terminal
- journalctl

## Commands Used

```bash
sudo apt update
journalctl --version
sudo journalctl -n 50
sudo journalctl -f
sudo journalctl -b
sudo journalctl -p err
sudo journalctl | grep Failed
```

## Output

The project displayed recent logs, boot logs, error logs, and failed events, allowing basic system log analysis.

## Skills Learned

- Linux Log Monitoring
- journalctl
- System Log Analysis
- Incident Monitoring
- Linux Administration

## Report

The complete implementation details and screenshots are available in the attached **Report.pdf** file.

## Conclusion

This project demonstrated how to monitor and analyze Linux system logs using journalctl to identify system events, troubleshoot issues, and improve security monitoring.
