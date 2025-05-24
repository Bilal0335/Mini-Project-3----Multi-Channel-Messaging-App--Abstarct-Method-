# 📱 Multi-Channel Messaging App

## Overview

This project demonstrates an abstract messaging system using Python's `abc` module.  
It supports sending messages through multiple channels—**Email** and **SMS**—by implementing a common interface.

Key features include:  
- Abstract base class enforcing common methods for all message senders  
- Concrete implementations for Email and SMS sending  
- Bulk message sending with retry on failure  
- Message logging to a file  
- Input validation for emails and phone numbers  

---

## Features

- Use of Abstract Base Class (`ABC`) to define messaging interface  
- Implementation of Email and SMS senders with connection management  
- Random failure simulation with retry mechanism  
- Validation for email addresses and phone numbers  
- Logging of sent messages to `message_log.txt`  

---
