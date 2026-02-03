# Log Analysis Report – Task 12

## Objective
The objective of this task is to analyze system authentication logs to detect suspicious activities such as failed login attempts and anomalies.

## Log Source
- Type: Authentication Logs
- File Name: sample_auth.log

## Observations
1. Multiple failed login attempts were detected for the user "admin" from IP address 192.168.1.10.
2. Repeated failures from the same IP indicate a possible brute-force attack.
3. A successful login was observed for user "root".
4. Normal login activity was observed for a valid user.

## Anomalies Detected
- Multiple failed login attempts from a single IP address.
- Login attempts using invalid users.

## Security Impact
These activities may indicate brute-force login attempts and unauthorized access attempts.

## Recommendations
- Block suspicious IP addresses.
- Enable account lockout policies.
- Implement SIEM tools for real-time alerting.

## Conclusion
Log monitoring helps in early detection of security incidents and improves overall system security.
