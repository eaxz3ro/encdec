## **Features**

### **Core Functionalities**

| Feature | Description |
|---------|-------------|
| **Base64 Encoding/Decoding** | Convert data to/from Base64 format |
| **Hexadecimal Encoding/Decoding** | Convert data to/from Hex format |
| **ROT13 Encoding/Decoding** | Apply ROT13 cipher to text |
| **Binary Encoding/Decoding** | Convert text to/from binary |
| **URL Encoding/Decoding** | Encode/decode URL strings |
| **Morse Code** | Convert text to/from Morse code |
| **A1Z26 Cipher** | Convert letters to numbers (A=1, Z=26) |
| **All Operations** | Apply all encoding/decoding methods simultaneously |

### **User Experience Features**

- **User-Friendly GUI** - Built with Tkinter for enhanced accessibility
- **Save Results** - Export results for documentation and further analysis
- **Cross-Platform** - Works on Windows, Linux, and macOS
- **Clear Output** - Reset and clear display areas for subsequent operations
- **Menu Options** - File and Help menus for better interaction
- **Error Handling** - Comprehensive exception management for reliability
- **Dropdown Selection** - Easy selection of encoding types and operations

---

## **Technologies Used**

### **Programming Language**

Python 3.x         

### **Frameworks**

| Framework | Purpose |
|-----------|---------|
| **Tkinter** | GUI framework |

### **Libraries & Modules**

| Library | Purpose |
|---------|---------|
| **base64** | Base64 encoding/decoding |
| **binascii** | Hexadecimal conversion |
| **codecs** | ROT13 encoding |
| **urllib.parse** | URL encoding/decoding |

---

## **Usage**

Before launching, ensure you have required Python libraries installed.

### **Launch Application**

```bash
python3 encdec.py
```

### **1. Select Operation**

Choose **"Encode"** or **"Decode"** from the Operation dropdown menu.

### **2. Select Encoding Type**

Choose from the following encoding methods:

| Encoding Type | Description |
|---------------|-------------|
| **base64** | Standard Base64 encoding |
| **hex** | Hexadecimal encoding |
| **rot13** | ROT13 cipher (Caesar cipher with 13 shifts) |
| **binary** | Binary representation |
| **url** | URL percent-encoding |
| **morse** | Morse code conversion |
| **a1z26** | Letter to number cipher (A=1, Z=26) |
| **all** | Apply all encoding methods simultaneously |

### **3. Enter Data**

Type or paste your data in the input field.

### **4. Execute Operation**

Click the **"Execute"** button to perform the operation.

### **5. View Output**

The result will appear in the output text area below.

### **6. Clear Output**

Click **"Clear Output"** to remove all text from the output area.

### **7. Save Results**

1. Click **File** → **Save Results**
2. Choose a filename and location
3. Click **Save**

