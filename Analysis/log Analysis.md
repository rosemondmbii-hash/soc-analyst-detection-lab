# Log Analysis

## 1. Multiple Failed Login Attempts

- User: admin  
- IP Address: 192.168.1.50  
- Activity: 4 failed login attempts followed by a successful login  

### Analysis
The repeated failed login attempts followed by a successful login indicate a likely brute force attack.  
The attacker may have successfully guessed or cracked the password.

### Risk Level
High

---

## 2. Suspicious File Activity

- User: jane.doe  
- File: finance.xlsx  
- Action: Accessed and deleted  

### Analysis
The deletion of a sensitive financial file suggests potential data tampering or unauthorized access.  
This activity could indicate insider threat or compromised credentials.

### Risk Level
High

---

## 3. Guest Account Activity

- IP Address: 10.0.0.5  
- Activity: Failed login followed by successful login  

### Analysis
Guest accounts should have restricted access.  
Successful login after failed attempts suggests weak authentication controls or misuse of guest privileges.

### Risk Level
Medium

---

## Correlation of Events

- Multiple suspicious activities occurred within a similar timeframe
- Unauthorized access and file deletion suggest post-compromise actions
- Possible attack chain:
  1. Brute force attack on admin account
  2. Unauthorized access gained
  3. Sensitive file accessed and deleted

---

## Conclusion

The observed activities strongly indicate a security breach involving unauthorized access and potential data compromise. Immediate investigation and containment actions are required.
