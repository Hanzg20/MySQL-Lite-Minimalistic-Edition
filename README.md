# MySQL Lite: Minimalistic Edition with Multi-CPU and Multi-OS Support

This repository offers a lightweight version of MySQL with compatibility for multiple CPU architectures and operating systems. The supported architectures include:

- **aarch**:
  - FeiTeng
  - KunPeng

- **alpha**:
  - ShenWei

- **mips**:
  - Loongson

- **x86**:
  - HaiGuang
  - ZhaoXin

**Windows**:
  - Support for AMD x86 architecture on Windows.

## Built-in Users

- **root/root** - Limited to local machine login.
- **test/test** - Allows login from any IP address.

## Built-in Database

- **test**

## Start/Stop Commands

- **Linux**:
  - Start: `mysql start`
  - Stop: `mysql stop`

- **Windows**:
  - Start: `start.bat`
  - Stop: `stop.bat`

## Command-Line Access

- **Linux**: `cmd.sh` (Prompts for the `test` user by default)
- **Windows**: `cmd.bat` (Prompts for the `test` user by default)

Feel free to modify, enhance, and contribute to this MySQL setup for various platforms. Your feedback and contributions are highly appreciated!

