# Day 05 – Web Basics (HTTP & HTTPS) – Visual Diagram

## How a Website Works
```

User Browser
|
| Request
v
Web Server
|
| Response
v
User Browser

```

## HTTP Communication (Not Secure)
```

Browser
|
| Plain Data
v
Internet
|
| Plain Data
v
Server

Data can be read if intercepted.

```

## HTTPS Communication (Secure)
```
Browser
|
| Encrypted Data
v
Internet
|
| Encrypted Data
v
Server

Data is protected using encryption.

```

## HTTP vs HTTPS (Visual Comparison)
```

HTTP
│
├── No encryption
├── Data visible in transit
└── Not secure for sensitive data

HTTPS
│
├── Uses encryption
├── Protects user data
└── Secure communication

```

## Why Web Basics Matter in Security
```

Web Application
|
v
User Input
|
v
If Security is Weak → Vulnerabilities
If Security is Strong → Data Protected
```
