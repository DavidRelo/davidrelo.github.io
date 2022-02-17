title: Error codes
---

# Error codes

- - -

This document provides possible causes and solutions for common errors related to the live streaming. 
<br>
<br>
- - -



## General errors

| Error code | Possible cause and solutions |
|-|-|
| 0 | No error occurs. |
| 1 | An unexpected error occurs. We recommend you contact us for solving the issue. |


## Room errors (100x range)


The error codes below return from the `createRoom` and `joinRoom` methods.

| Error code | Possible cause and solutions |
|-|-|
| 1001 | Room ID already exists.  You can try with a new Room ID. |
| 1002 | Room ID does not exist. Please check the Room ID before logging in to a room. |

## Co-host seat and other errors (200x range)

The error codes below return from the `takeSeat`, `leaveSeat`, and methods that called for other operations.

| Error code | Possible cause and solutions  |
|-|-|
| 2001 | Failed to take a seat because there is no seat available. You can try to take the seat again.|
| 2002 | Failed to take a seat because the seat info failed to be set. You can try to take the seat again.|
| 2003 | Failed to take a seat because you are already on a seat.|
| 2004 |  Operation failed because permission is denied. Please do not perform operations that are not authorized. |
| 2005 | Operation failed because the speaker seat has not been taken. You can try to take a speaker seat first. |
| 2006 | Invalid parameter. Please check the passed parameter. |

## Other SDK errors

- 7-digit error code starting with **10**: The RTC SDK related error. For more details, see [Real-Time Audio and Video - Error codes](https://docs.zegocloud.com/article/5548).
- 7-digit error code starting with **50**: The AI Effects SDK related error. For more details, see [AI Effects - Error codes](https://docs.zegocloud.com/article/9931).
- 7-digit error code starting with **60**: The ZIM SDK related error. For more details, see [ZIM - Error codes](https://docs.zegocloud.com/article/13792).
