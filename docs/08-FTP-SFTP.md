# FTP Basics

FTP (File Transfer Protocol) is used for transferring files over the Internet. It allows users to upload and download files from a server and is one of the oldest protocols for file transfer. 

## SFTP Explanation

SFTP (SSH File Transfer Protocol) is a secure version of FTP. It uses an encrypted connection to transfer files, ensuring that sensitive data is protected during transmission. 

## FTP vs FTPS vs SFTP Comparison Table
| Feature           | FTP            | FTPS           | SFTP            |
|-------------------|----------------|----------------|------------------|
| Security          | None           | SSL/TLS       | SSH              |
| Port              | 21             | 990            | 22               |
| Encryption        | No             | Yes            | Yes              |
| Authentication    | Username/Pass  | Username/Pass  | Username/Pass    |
| Transfer Modes    | Active/Passive  | Active/Passive | Usually Single   |

## FTP Commands
- `USER`: Specifies the username for authentication.
- `PASS`: Specifies the password for authentication.
- `RETR`: Retrieves a file from the server.
- `STOR`: Stores a file on the server.
- `QUIT`: Ends the session.

## Active and Passive Modes
- **Active Mode**: The client opens a port for data transfer and sends this information to the server.
- **Passive Mode**: The server opens a port for data transfer, which the client then connects to. This mode is often used when clients are behind firewalls.

## Security Considerations
- Always use encrypted protocols (like SFTP or FTPS) when transferring sensitive data.
- Regularly update passwords and restrict access to FTP accounts.

## Practice Questions (Pytania do Ćwiczeń)
1. Czym różni się FTP od SFTP?
2. Jakie są podstawowe komendy FTP?
3. Co to jest tryb pasywny i aktywny?

## Interactive Commands (Interaktywne Komendy)
- `ls`: Lists files in the current directory.
- `cd <directory>`: Changes the directory.
- `get <file>`: Downloads a file.
- `put <file>`: Uploads a file.