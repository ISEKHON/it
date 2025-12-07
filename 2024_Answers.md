# BCA Sem I - Introduction to Computers and IT
## Previous Year 2024 - Answers

---

## SECTION A (Any 6 questions × 2.5 marks = 15 marks)

### 1(a) What is the use of RAM? (2.5 marks)

**Answer:**
RAM (Random Access Memory) is the primary volatile memory used to temporarily store data and programs that are currently being processed by the CPU. It provides fast read/write access for running applications and the operating system. More RAM allows better multitasking and faster program execution. When power is off, all data in RAM is lost.

---

### 1(b) Write a note on Virus. (2.5 marks)

**Answer:**
A computer virus is malicious software that replicates itself and spreads to other files/computers. It attaches to host programs and activates when executed, causing damage like data corruption, system slowdown, or theft of information. Common types include boot sector, file infector, and macro viruses. Antivirus software detects and removes viruses using signature-based and heuristic methods.

---

### 1(c) What is the need of Computer? How to configure an Internet on it? (2.5 marks)

**Answer:**
**Need:** Computers are needed for fast calculations, data storage, automation, communication, education, entertainment, and business operations.

**Internet Configuration:**
1. Connect via Ethernet/Wi-Fi
2. Go to Control Panel → Network Settings
3. Select network adapter
4. Enter IP settings (automatic DHCP or manual)
5. Enter DNS servers
6. Test connection

---

### 1(d) What is the difference between OMR and OCR? (2.5 marks)

**Answer:**

| OMR | OCR |
|-----|-----|
| Detects marked areas on pre-printed forms | Recognizes and converts text characters |
| Used for answer sheets, surveys | Used for document scanning, text digitization |
| Only reads marks (circles/boxes) | Reads printed/handwritten text |
| Very high accuracy | Moderate accuracy (depends on quality) |

---

### 1(e) What is the role of cut, copy and paste in word processing? (2.5 marks)

**Answer:**
- **Cut (Ctrl+X):** Removes selected text/object and stores in clipboard for moving to new location
- **Copy (Ctrl+C):** Duplicates selected content to clipboard without removing original
- **Paste (Ctrl+V):** Inserts clipboard content at cursor position

These operations enable efficient text editing, reorganization, and duplication without retyping.

---

### 1(f) Is there any role of Software in the computer? (2.5 marks)

**Answer:**
Yes, software is essential. Hardware is useless without software. Software provides instructions that tell hardware what to do. Types include:
- **System Software:** OS manages hardware (Windows, Linux)
- **Application Software:** Performs user tasks (MS Office, browsers)
- **Utility Software:** Maintains system (antivirus, disk cleaners)

Without software, computers cannot function.

---

### 1(g) Write the steps to install LibreOffice. (2.5 marks)

**Answer:**
1. Download LibreOffice installer from www.libreoffice.org
2. Double-click the downloaded .exe/.msi file
3. Click "Next" on welcome screen
4. Choose installation type (Typical/Custom)
5. Select installation folder
6. Click "Install" button
7. Wait for installation to complete
8. Click "Finish" and launch LibreOffice

---

### 1(h) Write the limitations of Optical Storage devices. (2.5 marks)

**Answer:**
1. **Low capacity:** CDs (700MB), DVDs (4.7GB) - insufficient for modern needs
2. **Fragile:** Scratches damage data permanently
3. **Slow:** Read/write speeds much slower than SSDs/HDDs
4. **Limited rewrites:** CD-RW/DVD-RW have limited write cycles
5. **Declining support:** Modern laptops often lack optical drives
6. **Replaced by:** USB drives and cloud storage

---

## SECTION B (Answer 1 question × 15 marks = 15 marks)

### 2. Explain the various parts of computers with its functional diagram. (15 marks)

**Answer:**

A computer system consists of five main functional units that work together:

#### 1. Input Unit (3 marks)
- **Function:** Accepts data and instructions from external sources
- **Process:** Converts human-readable data into binary (machine-readable) form
- **Examples:** Keyboard, mouse, scanner, microphone, webcam
- **Working:** User enters data → Input device converts to electrical signals → Sends to memory

#### 2. Storage Unit / Memory (3 marks)
**Primary Storage (RAM):**
- Volatile memory for temporary storage
- Holds currently running programs and active data
- Fast access but erases when power off

**Secondary Storage (Hard Disk/SSD):**
- Permanent storage for OS, programs, files
- Non-volatile (data persists after power off)
- Larger capacity but slower than RAM

#### 3. Central Processing Unit (CPU) - The Brain (4 marks)

**a) Arithmetic Logic Unit (ALU):**
- Performs arithmetic operations (+, -, ×, ÷)
- Performs logical operations (AND, OR, NOT, comparisons)
- Does all actual calculations and data processing

**b) Control Unit (CU):**
- Controls and coordinates all computer operations
- Fetches instructions from memory
- Decodes instructions
- Directs data flow between units
- Acts as traffic controller for all operations

#### 4. Output Unit (2 marks)
- **Function:** Presents processed results to users
- **Process:** Converts binary data back to human-readable form
- **Examples:** Monitor, printer, speakers, projector
- **Working:** Receives results from CPU → Converts to readable format → Displays/prints

#### 5. Inter-relationship (3 marks)

**Functional Diagram:**
```
┌─────────────────────────────────────────────────────┐
│                                                     │
│  INPUT DEVICES  →  MEMORY (RAM)  ↔  CPU            │
│  (Keyboard,        (Temporary)       ├─ ALU        │
│   Mouse)                             └─ CU         │
│                        ↕                ↕           │
│                  SECONDARY          OUTPUT         │
│                  STORAGE            DEVICES        │
│                  (HDD/SSD)          (Monitor,      │
│                  (Permanent)         Printer)      │
│                                                     │
└─────────────────────────────────────────────────────┘
```

**Working Process:**
1. Input device sends data to memory (RAM)
2. CPU fetches data from memory
3. Control Unit coordinates operations
4. ALU processes the data (calculations)
5. Results stored back in memory
6. Output device displays results
7. Important data saved to secondary storage

All units work together in a coordinated manner under the control of the Control Unit to complete tasks efficiently.

---

### 3. Name any five input devices and explain any two out of these with its diagram. (15 marks)

**Answer:**

#### Five Input Devices: (3 marks)
1. Keyboard
2. Mouse
3. Scanner
4. Barcode Reader
5. Touch Screen

#### Detailed Explanation:

### 1. KEYBOARD (6 marks)

**Definition:**
A keyboard is a primary text input device that allows users to enter alphanumeric data and commands into the computer.

**Types of Keys:**
- **Alphanumeric Keys:** Letters (A-Z) and numbers (0-9)
- **Function Keys:** F1-F12 (shortcuts)
- **Control Keys:** Ctrl, Alt, Shift, Windows key
- **Navigation Keys:** Arrow keys, Home, End, Page Up/Down
- **Numeric Keypad:** Calculator-style number entry
- **Special Keys:** Enter, Backspace, Delete, Tab, Esc

**Types of Keyboards:**
- Standard keyboard (104/108 keys)
- Wireless keyboard (Bluetooth/RF)
- Ergonomic keyboard (comfort design)
- Gaming keyboard (mechanical switches, RGB)

**Working:**
When a key is pressed, a scanning circuit identifies which key was pressed and sends the corresponding ASCII/Unicode code to the computer.

**Diagram:**
```
┌────────────────────────────────────────────────────┐
│  [Esc] [F1][F2][F3]...[F12]        [PrtSc][ScLk]  │
│                                                     │
│  [`][1][2][3][4][5][6][7][8][9][0][-][=][Backsp]  │
│  [Tab][Q][W][E][R][T][Y][U][I][O][P][ [ ][ ] [\]  │
│  [Caps][A][S][D][F][G][H][J][K][L][;]['][Enter]   │
│  [Shift][Z][X][C][V][B][N][M][,][.][/][Shift]     │
│  [Ctrl][Win][Alt][ Spacebar ][Alt][Win][Ctrl]     │
│                                                     │
│                    [Numeric Keypad]                │
│                    [7][8][9][/]                    │
│                    [4][5][6][*]                    │
│                    [1][2][3][-]                    │
│                    [0][.][Enter][+]                │
└────────────────────────────────────────────────────┘
```

**Advantages:**
- Fast text entry
- Widely available and affordable
- Shortcuts increase productivity

**Disadvantages:**
- Requires typing skills
- Prone to errors
- Physical wear over time

---

### 2. BARCODE READER (6 marks)

**Definition:**
A barcode reader (scanner) is an automatic data capture device that reads printed barcodes and converts them into digital data.

**Working Principle:**
1. Scanner emits light (laser or LED) on barcode
2. Black bars absorb light, white spaces reflect it
3. Sensor detects the reflected light pattern
4. Decoder converts pattern into alphanumeric data
5. Data sent to computer

**Types of Barcodes:**
- **1D Barcodes:** Linear bars (UPC, EAN, Code 39, Code 128)
  - Store 8-20 characters
  - Used for product identification
  
- **2D Barcodes:** QR codes, PDF417, Data Matrix
  - Store much more data (up to 7,000 characters)
  - Can contain URLs, contact info, images

**Types of Scanners:**
- **Pen-type:** Manual swipe across barcode
- **Laser Scanner:** Red laser beam (most common in retail)
- **CCD Scanner:** Multiple LEDs for close-range
- **Image Scanner:** Camera-based (smartphones)

**Diagram:**
```
                    Barcode Reader
                         
         ┌──────────────────────┐
         │   Barcode Scanner    │
         │  ┌────────────────┐  │
         │  │  Light Source  │  │
         │  │   (Laser/LED)  │  │
         │  └────────┬───────┘  │
         │           │           │
         │           ↓ Light     │
         │    ┌──────────────┐  │
         │    │  |||||||||||  │  │ ← Barcode
         │    │  |||||||||||  │  │
         │    └──────────────┘  │
         │           ↑ Reflected│
         │    ┌──────┴───────┐  │
         │    │   Sensor/    │  │
         │    │   Detector   │  │
         │    └──────┬───────┘  │
         │           │           │
         │    ┌──────▼───────┐  │
         │    │   Decoder    │  │
         │    └──────┬───────┘  │
         │           │           │
         └───────────┼───────────┘
                     ↓
              To Computer
```

**Applications:**
- **Retail:** Product checkout, pricing
- **Inventory:** Stock tracking, warehouse management
- **Libraries:** Book tracking and lending
- **Healthcare:** Patient identification, medication tracking
- **Logistics:** Package tracking (courier services)
- **Ticketing:** Event tickets, boarding passes

**Advantages:**
- Very fast data entry (1-2 seconds)
- Extremely accurate (99.9%+)
- Reduces manual entry errors
- Cost-effective
- Easy to implement

**Disadvantages:**
- Requires printed barcode
- Damaged/smudged barcodes can't be read
- Line-of-sight needed
- Limited data storage (1D barcodes)

---

## SECTION C (Answer 1 question × 15 marks = 15 marks)

### 4. Explain the working of Printer and Plotter with its diagram. (15 marks)

**Answer:**

## PRINTER (8 marks)

### Definition:
A printer is an output device that produces hard copy (paper) output of digital documents and images.

### Types and Working:

#### 1. INKJET PRINTER (4 marks)

**Technology:**
- Sprays tiny droplets of liquid ink onto paper
- Uses CMYK ink cartridges (Cyan, Magenta, Yellow, Black)
- Thermal or piezoelectric mechanism to eject ink

**Working Process:**
1. Document sent from computer to printer
2. Printer driver converts to printable format
3. Print head moves horizontally across paper
4. Nozzles spray ink droplets in pattern
5. Paper advances vertically
6. Process repeats line by line until complete

**Diagram:**
```
        Inkjet Printer Working
        
    Ink Cartridges (CMYK)
         ↓  ↓  ↓  ↓
    ┌────────────────────┐
    │   Print Head       │
    │  [Nozzles (50-300)]│ ← Moves left-right
    └─────────┬──────────┘
              ↓ Ink droplets
    ═══════════════════════
    ║    Paper (A4)      ║ ← Moves up
    ═══════════════════════
         ↑
    Paper Feed Roller
```

**Specifications:**
- Print quality: 1200-4800 DPI
- Speed: 5-15 pages per minute
- Cost: Printer cheap, ink expensive

**Advantages:**
✅ Excellent photo quality
✅ Good color reproduction
✅ Quiet operation
✅ Affordable initial cost

**Disadvantages:**
❌ Expensive ink cartridges
❌ Ink dries if unused
❌ Slow for bulk printing

---

#### 2. LASER PRINTER (4 marks)

**Technology:**
- Uses laser beam, toner powder, and heat
- Electrostatic printing process
- Fast and high-quality

**Working Process (6 steps):**
1. **Charging:** Drum gets uniform negative charge
2. **Writing:** Laser beam draws image on drum (neutralizes charge)
3. **Developing:** Negatively charged toner sticks to neutralized areas
4. **Transfer:** Toner transferred to paper (positively charged)
5. **Fusing:** Heat and pressure fuse toner permanently to paper
6. **Cleaning:** Drum cleaned for next page

**Diagram:**
```
       Laser Printer Working Process
       
  [Laser Beam] → ┌─────────────┐
                  │ Rotating    │
                  │ Mirror      │
                  └──────┬──────┘
                         ↓
                  ┌─────────────┐
    Toner  →     │ Drum        │
    Cartridge    │ (charged)   │
                  └──────┬──────┘
                         ↓ Toner pattern
                  ═══════════════
                  ║    Paper   ║
                  ═══════════════
                         ↓
                  ┌──────────────┐
                  │ Fuser Unit   │
                  │ (Heat 200°C) │
                  └──────┬───────┘
                         ↓
                   Printed Page
```

**Specifications:**
- Print quality: 600-2400 DPI
- Speed: 20-100 pages per minute
- Duty cycle: Thousands of pages/month

**Advantages:**
✅ Very fast
✅ Low cost per page
✅ Sharp text quality
✅ Toner doesn't dry out
✅ Ideal for office use

**Disadvantages:**
❌ Expensive initial cost
❌ Large and heavy
❌ High power consumption

---

## PLOTTER (7 marks)

### Definition:
A plotter is a specialized output device for printing large-format graphics, engineering drawings, and architectural blueprints with high precision.

### Difference from Printer:
- **Plotter:** Draws continuous vector lines using pens
- **Printer:** Creates raster images using dots/pixels

### Types:

#### 1. FLATBED PLOTTER (3.5 marks)

**Description:**
- Paper lies flat on horizontal table surface
- Pen moves in both X and Y directions
- Suitable for rigid materials (cardboard, plastic)

**Working:**
1. Paper placed on flat table and secured
2. Pen holder moves along X-axis rail
3. Entire rail assembly moves along Y-axis
4. Pen raises/lowers to draw/not draw
5. Vector graphics drawn with continuous lines
6. Can use multiple colored pens

**Diagram:**
```
       Flatbed Plotter
       
    Y-axis rail (moves ↑↓)
         │
    ┌────┴────┐
    │  Pen    │ ← Moves ←→ along X-axis
    └────┬────┘
         │ Pen down
    ┌────▼─────────────────┐
    │                      │
    │   Paper on Flat Bed │
    │   (secured)          │
    │                      │
    └──────────────────────┘
    
    Drawing area: Up to A0 size (33×47 inches)
```

**Features:**
- Very high accuracy (±0.1mm)
- Can plot on various materials
- Slow (detailed drawings take time)
- Expensive

---

#### 2. DRUM PLOTTER (3.5 marks)

**Description:**
- Paper wrapped around rotating drum
- Pen moves left-right (X-axis)
- Drum rotates forward-backward (Y-axis)
- Suitable for long continuous plots

**Working:**
1. Paper loaded onto cylindrical drum
2. Drum rotates for Y-axis movement
3. Pen carriage moves left-right for X-axis
4. Combination creates any shape
5. Pen lifts when not drawing
6. Paper advances continuously

**Diagram:**
```
      Drum Plotter
      
   Pen Carriage (moves ←→)
        ↓
    ┌───────┐
    │  Pen  │
    └───┬───┘
        │ Drawing
    ╔═══▼═══════════╗
    ║   Rotating    ║ ← Drum rotates (↑↓ movement)
    ║   Drum        ║
    ║   (Paper      ║
    ║    wrapped)   ║
    ╚═══════════════╝
    
    Output: Long continuous plot
```

**Features:**
- Faster than flatbed
- Can handle very long plots (meters)
- Less expensive than flatbed
- Paper size limited by drum width

---

### Applications of Plotters:
1. **Architecture:** Building blueprints, floor plans
2. **Engineering:** CAD drawings, circuit designs
3. **Construction:** Site plans, structural diagrams
4. **Cartography:** Maps, topographical charts
5. **Advertising:** Large banners, posters
6. **Fashion:** Textile patterns, garment designs

### Plotter vs Printer Comparison:

| Feature | Plotter | Printer |
|---------|---------|---------|
| Purpose | Large graphics, technical drawings | Documents, photos |
| Technology | Draws continuous lines (vector) | Dots/pixels (raster) |
| Size | Very large (A0, A1) | Standard (A4, A3) |
| Quality | Vector (infinitely scalable) | Raster (pixelated if enlarged) |
| Speed | Slow | Fast |
| Cost | Very expensive | Affordable |

---

## (Continuing with remaining sections...)
