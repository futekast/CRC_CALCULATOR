# CRC & Checksum Calculator

A lightweight desktop GUI tool for calculating multiple CRC and checksum algorithms with a clean and user-friendly interface.

Designed for engineers, developers, and technicians working with embedded systems, communication protocols, and data validation.

---

## Features

- Supports multiple CRC and checksum algorithms
- Real-time input preview and formatting
- Flexible input modes (HEX and String)
- Automatic byte parsing and validation
- One-click calculation of all algorithms
- Double-click any result to copy to clipboard
- Clean and consistent output formatting
- Lightweight standalone executable (no installation required)

---

## Supported Algorithms

### Checksums
- Checksum/FUTEK (Weighted additive 8-bit checksum)

### CRC-8
- CRC-8/SMBUS  
- CRC-8/MAXIM  

### CRC-16
- CRC-16/ARC  
- CRC-16/MAXIM  
- CRC-16/MODBUS  
- CRC-16/MODBUS (Reversed)  

### CRC-32
- CRC-32/IEEE  

### CRC-64
- CRC-64/ECMA-182  

---

## Input Modes

### HEX Mode

Accepts multiple formats:

0x12 0x34 0x56  
12 34 56  
123456  

---

### String Mode

Treats input as ASCII/UTF-8:

123456789  
HelloWorld  

---

## Input Preview

The preview panel shows how your input is interpreted:

- Byte Count – Total number of bytes  
- HEX Bytes – Formatted byte representation  
- ASCII View – Printable characters  
- Decimal Bytes – Byte values in decimal  

---

## Results

Displays all supported algorithms simultaneously:

- Algorithm name  
- Output width  
- Calculated result  

### Copy Feature

- Double-click any row to copy  
- Or use the Copy Result button  

---

## Usage

1. Select input type (HEX or String)  
2. Enter or paste your data  
3. Click Calculate  
4. View results  
5. Double-click any result to copy  

---

## Notes

- This tool performs calculation only and does not modify input data  
- Byte order is handled per algorithm definition  

---

## License

This repository contains the GUI tool only.

Underlying algorithm implementations may be proprietary and are not distributed as source code in this repository.