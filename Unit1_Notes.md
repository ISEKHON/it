# UNIT 1: Introduction to Computers and Input Devices

## 1. Computer as a System

### What is a Computer?
A **computer** is an electronic device that accepts data (input), processes it according to instructions (program), and produces meaningful information (output). It works as a complete system with interconnected components.

### Basic Concepts

**Data vs Information:**
- **Data**: Raw facts and figures without meaning (e.g., 95, 87, 72)
- **Information**: Processed data with meaning (e.g., Student scored 95% in exams)

**Characteristics of Computers:**
1. **Speed**: Executes millions of instructions per second (measured in MIPS - Million Instructions Per Second)
2. **Accuracy**: Performs calculations with 100% accuracy (follows GIGO - Garbage In Garbage Out)
3. **Storage**: Can store vast amounts of data permanently
4. **Diligence**: Works continuously without fatigue or boredom
5. **Versatility**: Can perform multiple types of tasks
6. **Automation**: Can work automatically once programmed

### Functional Units and Their Inter-relation

A computer system has **five main functional units** that work together:

#### 1. Input Unit
- **Purpose**: Accepts data and instructions from users
- **Function**: Converts human-readable data into computer-readable form (binary)
- **Examples**: Keyboard, mouse, scanner
- **How it works**: Takes external data → Converts to binary signals → Sends to memory

#### 2. Storage Unit (Memory)
- **Purpose**: Stores data and instructions
- **Two types**:
  - **Primary Storage (RAM)**: Temporary, fast, used during processing
  - **Secondary Storage (Hard Disk)**: Permanent, slower, stores data long-term
- **Function**: Holds input data, intermediate results, final output, and programs

#### 3. Central Processing Unit (CPU) - The Brain
The CPU has two main components:

**a) Arithmetic Logic Unit (ALU)**
- Performs all arithmetic operations (+, -, ×, ÷)
- Performs logical operations (AND, OR, NOT, comparisons like >, <, =)
- Does all actual data processing

**b) Control Unit (CU)**
- Controls and coordinates all computer operations
- Fetches instructions from memory
- Decodes instructions
- Directs data flow between units
- Acts like a traffic controller

#### 4. Output Unit
- **Purpose**: Presents processed information to users
- **Function**: Converts computer-readable data (binary) into human-readable form
- **Examples**: Monitor, printer, speakers
- **How it works**: Receives binary data from CPU → Converts to readable form → Displays/prints

#### 5. Communication Between Units
```
INPUT → MEMORY ↔ CPU (ALU + CU) ↔ MEMORY → OUTPUT
              ↓
        STORAGE (Secondary)
```

**Working Process:**
1. Input device sends data to memory
2. CPU fetches data from memory
3. ALU processes the data
4. CU controls the entire operation
5. Results stored back in memory
6. Output device displays results

---

## 2. Milestones in Hardware and Software

### Hardware Milestones (Evolution of Computers)

#### First Generation (1940-1956): Vacuum Tubes
- **Technology**: Used vacuum tubes for circuitry
- **Memory**: Magnetic drums
- **Size**: Room-sized, very large
- **Speed**: Very slow (milliseconds)
- **Heat**: Generated enormous heat
- **Cost**: Extremely expensive
- **Examples**: ENIAC, UNIVAC, EDVAC
- **Programming**: Machine language (0s and 1s)
- **Drawbacks**: Unreliable, consumed lots of power, limited programming

#### Second Generation (1956-1963): Transistors
- **Technology**: Transistors replaced vacuum tubes
- **Memory**: Magnetic core memory
- **Size**: Smaller than first generation
- **Speed**: Faster (microseconds)
- **Heat**: Less heat generation
- **Cost**: Less expensive
- **Examples**: IBM 1401, IBM 7094, CDC 1604
- **Programming**: Assembly language, high-level languages (COBOL, FORTRAN) emerged
- **Advantages**: More reliable, smaller, consumed less power

#### Third Generation (1964-1971): Integrated Circuits (IC)
- **Technology**: ICs (multiple transistors on single silicon chip)
- **Memory**: Semiconductor memory
- **Size**: Much smaller
- **Speed**: Very fast (nanoseconds)
- **Examples**: IBM 360 series, PDP-8, PDP-11
- **Programming**: High-level languages became standard
- **Operating System**: Multiprogramming, time-sharing OS developed
- **Advantages**: Portable, reliable, efficient, affordable

#### Fourth Generation (1971-Present): Microprocessors
- **Technology**: LSI (Large Scale Integration) and VLSI (Very Large Scale Integration)
- **Key Innovation**: Entire CPU on a single chip (microprocessor)
- **Size**: Desktop computers, laptops, mobile devices
- **Speed**: Extremely fast (picoseconds)
- **Examples**: Intel 4004 (first microprocessor), IBM PC, Apple Macintosh
- **Memory**: Semiconductor chips (RAM, ROM)
- **Features**: GUIs, networking, internet connectivity
- **Advantages**: Very small, cheap, reliable, portable

#### Fifth Generation (Present-Future): Artificial Intelligence
- **Technology**: ULSI (Ultra Large Scale Integration)
- **Focus**: AI, machine learning, natural language processing
- **Features**: Voice recognition, parallel processing, quantum computing
- **Examples**: AI systems, expert systems, neural networks
- **Goal**: Computers that can think, learn, and make decisions

### Software Milestones

#### 1. Machine Language Era (1940s)
- Programs written in binary (0s and 1s)
- Extremely difficult to write and debug
- Machine-specific (not portable)

#### 2. Assembly Language Era (1950s)
- Symbolic codes instead of binary
- Easier than machine language
- Still machine-dependent
- Used mnemonics (ADD, SUB, MOV)

#### 3. High-Level Languages (1960s onwards)
- **FORTRAN (1957)**: First high-level language, for scientific computing
- **COBOL (1959)**: For business applications
- **BASIC (1964)**: Beginner-friendly language
- **C (1972)**: System programming language
- **Pascal (1970)**: Structured programming

#### 4. Modern Programming Era (1980s-Present)
- **Object-Oriented**: C++, Java, Python
- **Web Technologies**: JavaScript, PHP, HTML
- **Mobile Development**: Swift, Kotlin
- **Data Science**: Python, R

#### 5. Operating Systems Evolution
- **1960s**: Batch processing systems
- **1970s**: UNIX, time-sharing systems
- **1980s**: MS-DOS, GUI-based systems
- **1990s**: Windows 95/98, Linux
- **2000s**: Windows XP/7/10, macOS, Android, iOS
- **Present**: Cloud-based OS, mobile OS dominance

---

## 3. Types of Computer Applications

### A. Batch Oriented Processing
- **Definition**: Jobs are collected in batches and processed together without user interaction
- **Characteristics**:
  - No direct user interaction during processing
  - Jobs queued and executed sequentially
  - Output generated after completion
- **Advantages**:
  - Efficient for large volumes
  - No idle time for computer
  - Cost-effective
- **Disadvantages**:
  - No immediate response
  - Errors detected late
- **Examples**:
  - Payroll processing (monthly salary calculation)
  - Electricity bill generation
  - Bank statement generation
  - Exam result processing

### B. Online Processing
- **Definition**: Data is processed immediately as it is entered
- **Characteristics**:
  - Direct user-computer interaction
  - Immediate response
  - Real-time data entry and retrieval
- **Advantages**:
  - Immediate feedback
  - Up-to-date information
  - User can make corrections instantly
- **Disadvantages**:
  - Requires constant availability
  - More expensive
- **Examples**:
  - Online banking transactions
  - Railway/airline reservation systems
  - E-commerce shopping
  - ATM transactions
  - Student registration systems

### C. Real-Time Processing
- **Definition**: Data is processed instantly, and results affect subsequent inputs immediately
- **Characteristics**:
  - Immediate processing with zero delay
  - Time-critical applications
  - System responds within strict time constraints
- **Types**:
  1. **Hard Real-Time**: Missing deadline causes system failure (aircraft control)
  2. **Soft Real-Time**: Missing deadline degrades performance (video streaming)
- **Advantages**:
  - Instant response
  - Critical for time-sensitive tasks
  - High accuracy
- **Examples**:
  - Air traffic control systems
  - Medical monitoring systems (ICU)
  - Missile guidance systems
  - Stock market trading
  - Industrial process control
  - Automated manufacturing

---

## 4. Applications of Computers

### 1. Education
- **E-learning platforms**: Online courses, video lectures
- **Virtual classrooms**: Zoom, Google Meet
- **Computer-Based Training (CBT)**: Interactive learning
- **Smart classrooms**: Digital boards, multimedia presentations
- **Online examinations**: Automated testing and evaluation
- **Digital libraries**: Access to vast resources
- **Research**: Data analysis, simulations

### 2. Banking and Finance
- **Online banking**: 24/7 account access
- **ATMs**: Cash withdrawal, deposits
- **NEFT/RTGS**: Electronic fund transfers
- **Credit/Debit cards**: Cashless transactions
- **Stock market**: Electronic trading
- **Loan processing**: Automated approval systems
- **Fraud detection**: AI-based security

### 3. Healthcare
- **Patient records**: Electronic Health Records (EHR)
- **Diagnostic tools**: CT scan, MRI, X-ray analysis
- **Telemedicine**: Remote consultations
- **Drug research**: Molecular modeling
- **Surgery**: Robot-assisted operations
- **Hospital management**: Appointment scheduling, billing
- **Wearable devices**: Health monitoring

### 4. Business and Commerce
- **E-commerce**: Online shopping (Amazon, Flipkart)
- **Inventory management**: Stock tracking
- **Accounting**: Automated bookkeeping
- **Payroll**: Salary calculation
- **Customer Relationship Management (CRM)**
- **Digital marketing**: Social media, email campaigns
- **Video conferencing**: Business meetings

### 5. Communication
- **Email**: Instant messaging worldwide
- **Social media**: Facebook, Instagram, Twitter
- **Video calls**: Skype, WhatsApp, Zoom
- **VoIP**: Internet telephony
- **Messaging apps**: WhatsApp, Telegram

### 6. Entertainment
- **Streaming**: Netflix, YouTube, Spotify
- **Gaming**: PC games, online multiplayer
- **Animation**: Movies, cartoons (Pixar, DreamWorks)
- **Music production**: Digital audio workstations
- **Video editing**: Professional film editing

### 7. Science and Research
- **Space exploration**: Satellite control, data analysis
- **Weather forecasting**: Climate modeling
- **Scientific simulations**: Particle physics, chemistry
- **DNA sequencing**: Genetic research
- **Astronomical calculations**: Universe mapping

### 8. Government
- **E-governance**: Digital India initiatives
- **Aadhaar**: Unique identification system
- **Income tax filing**: Online returns
- **Passport services**: Online applications
- **Election management**: Voter lists, EVM machines
- **Land records**: Digital property records

### 9. Transportation
- **GPS navigation**: Google Maps, route planning
- **Traffic management**: Signal control, monitoring
- **Railway reservations**: IRCTC
- **Airlines**: Booking, flight management
- **Metro systems**: Automated ticketing

### 10. Defense
- **Missile systems**: Guidance and control
- **Surveillance**: Satellite monitoring
- **Encryption**: Secure communication
- **Simulations**: Training programs
- **Intelligence**: Data analysis

---

## 5. Input Devices (Detailed)

### A. Keyboard
- **Type**: Text input device
- **Function**: Enters alphanumeric data and commands
- **Keys**:
  - **Alphanumeric keys**: Letters (A-Z), numbers (0-9)
  - **Function keys**: F1-F12 (shortcuts)
  - **Control keys**: Ctrl, Alt, Shift, Windows key
  - **Navigation keys**: Arrow keys, Home, End, Page Up/Down
  - **Numeric keypad**: Calculator-style number entry
  - **Special keys**: Enter, Backspace, Delete, Tab, Esc
- **Types**:
  - Standard keyboard (104/108 keys)
  - Wireless keyboard (Bluetooth)
  - Ergonomic keyboard (comfort design)
  - Gaming keyboard (mechanical switches)
- **Advantages**: Fast text entry, widely available, cheap
- **Disadvantages**: Requires typing skills, prone to errors

### B. Mouse
- **Type**: Pointing device
- **Function**: Controls cursor, selects items, navigates GUI
- **Components**:
  - Left button (select, click)
  - Right button (context menu)
  - Scroll wheel (page navigation)
  - Sensor (optical/laser for movement detection)
- **Types**:
  - **Mechanical mouse**: Ball-based (older)
  - **Optical mouse**: LED light sensor
  - **Laser mouse**: More precise than optical
  - **Wireless mouse**: Bluetooth/RF connection
  - **Trackball**: Stationary, ball on top
  - **Touchpad**: Laptop integrated pointer
- **Operations**:
  - **Click**: Single press
  - **Double-click**: Quick two presses
  - **Right-click**: Context menu
  - **Drag and drop**: Move items
  - **Scroll**: Navigate pages
- **Advantages**: Easy to use, precise control, intuitive
- **Disadvantages**: Requires flat surface, wrist strain

### C. Light Pen
- **Type**: Pointing and drawing device
- **Function**: Direct screen interaction, drawing, selection
- **How it works**:
  - Light-sensitive pen touches screen
  - Photocell detects screen position
  - Coordinates sent to computer
- **Uses**:
  - CAD (Computer-Aided Design) applications
  - Graphic design
  - Signature capture
  - Medical imaging annotation
- **Advantages**: Direct screen interaction, precise drawing
- **Disadvantages**: Expensive, arm fatigue, limited use

### D. Touch Screen
- **Type**: Input and output device (dual purpose)
- **Function**: Direct finger/stylus interaction with display
- **Technology Types**:
  1. **Resistive**: Pressure-sensitive layers (cheaper, less accurate)
  2. **Capacitive**: Electrical charge detection (smartphones, tablets)
  3. **Infrared**: Light beam interruption
  4. **Surface Acoustic Wave**: Ultrasonic waves
- **Gestures**:
  - Tap (click)
  - Double tap (open)
  - Swipe (scroll)
  - Pinch (zoom in/out)
  - Long press (context menu)
- **Uses**:
  - Smartphones and tablets
  - ATM machines
  - Information kiosks
  - Point-of-sale (POS) systems
  - Car navigation
- **Advantages**: Intuitive, no external device needed, fast input
- **Disadvantages**: Screen gets dirty, not precise for detailed work

### E. Bar Code Reader (Scanner)
- **Type**: Automatic data capture device
- **Function**: Reads printed barcodes and converts to digital data
- **How it works**:
  1. Scanner emits light (laser/LED)
  2. Light reflects off barcode (black absorbs, white reflects)
  3. Sensor detects reflected pattern
  4. Decodes into numbers/data
- **Types of Barcodes**:
  - **1D Barcodes**: Linear lines (UPC, EAN, Code 39)
  - **2D Barcodes**: QR codes, PDF417 (store more data)
- **Uses**:
  - Retail checkout (product pricing)
  - Inventory management
  - Library book tracking
  - Package tracking (courier services)
  - Attendance systems
  - Ticket verification
- **Advantages**: Fast, accurate, reduces manual entry, cost-effective
- **Disadvantages**: Requires printed barcode, damaged codes can't be read

### F. Joystick
- **Type**: Gaming and control device
- **Function**: Controls movement in games and simulations
- **Components**:
  - Stick (moves in all directions)
  - Base (contains sensors)
  - Buttons (action controls)
  - Triggers (additional controls)
- **Working**:
  - Stick movement changes resistance/voltage
  - Sensors detect direction and angle
  - Signals sent to computer
- **Uses**:
  - Video gaming (flight simulators, racing games)
  - Aircraft/drone control
  - Wheelchair control
  - Industrial machinery operation
  - CAD applications
- **Advantages**: 360° movement, good for gaming, ergonomic
- **Disadvantages**: Not suitable for text entry, requires practice

### G. Source Data Automation Devices

These devices **automatically capture data** from source documents without manual typing:

#### 1. MICR (Magnetic Ink Character Recognition)
- **Function**: Reads magnetic ink characters
- **Technology**:
  - Special magnetic ink used for printing
  - MICR reader magnetizes characters
  - Reads the magnetic pattern
  - Converts to digital data
- **Characters**: E-13B font (0-9 and 4 special symbols)
- **Uses**:
  - **Bank cheque processing** (most common)
  - Reads cheque number, account number, bank code
  - Fast, accurate cheque clearing
- **Cheque MICR Code**:
  ```
  ⑈123456⑈ ⑆789012⑆ 34
  Cheque#   Account#  Bank Code
  ```
- **Advantages**: 
  - Very secure (hard to forge magnetic ink)
  - High accuracy
  - Fast processing (thousands of cheques/hour)
  - Works even if overwritten
- **Disadvantages**: Expensive equipment, only specific fonts

#### 2. OMR (Optical Mark Recognition)
- **Function**: Detects marked areas on pre-printed forms
- **Technology**:
  - Light source illuminates paper
  - Marked areas reflect less light (darker)
  - Sensor detects darkness
  - Identifies marked positions
- **Uses**:
  - **Exam answer sheets** (objective questions)
  - Survey forms (opinion polls)
  - Attendance sheets (mark present/absent)
  - Lottery tickets
  - Election ballots
- **Requirements**:
  - Pre-printed forms with designated boxes
  - Dark pencil/pen marks
  - Proper alignment
- **Advantages**: 
  - Fast data entry (thousands of sheets/hour)
  - High accuracy
  - Cost-effective for bulk processing
  - Eliminates manual data entry
- **Disadvantages**: 
  - Only reads marks (not text)
  - Requires special forms
  - Errors if marks unclear

#### 3. OCR (Optical Character Recognition)
- **Function**: Converts printed/handwritten text to digital text
- **Technology**:
  - Scanner captures document image
  - Software analyzes character shapes
  - Matches with stored patterns
  - Converts to editable text
- **Types**:
  - **Printed OCR**: Reads typed/printed text
  - **Handwriting OCR (ICR)**: Reads handwritten text (less accurate)
- **Uses**:
  - Scanning books/documents to digital format
  - Converting PDFs to editable Word documents
  - Passport reading at airports
  - Vehicle number plate recognition
  - Invoice processing
  - Business card scanning
- **Examples**:
  - Google Lens
  - Adobe Acrobat OCR
  - Microsoft Office Lens
- **Advantages**:
  - Converts paper to digital
  - Searchable documents
  - Saves typing time
  - Preserves old documents
- **Disadvantages**:
  - Accuracy depends on print quality
  - Errors with poor handwriting
  - Formatting may be lost

### H. Screen Assisted Data Entry Devices

#### Portable/Handheld Terminals for Data Collection
- **Type**: Mobile data capture devices
- **Function**: Collect data at remote locations and sync with central system
- **Features**:
  - Built-in display screen
  - Keypad or touchscreen
  - Barcode scanner (often integrated)
  - Wireless connectivity (Wi-Fi, 4G)
  - Battery-powered
  - Rugged design
- **Working**:
  1. User enters/scans data on-site
  2. Data stored in device memory
  3. Later synced with main database
  4. Can work offline and upload later
- **Uses**:
  - **Inventory counting**: Warehouse stock verification
  - **Delivery services**: Package tracking, signature capture
  - **Retail**: Price checking, stock updates
  - **Healthcare**: Patient data collection at bedside
  - **Field surveys**: Market research, census
  - **Meter reading**: Electricity, gas, water
  - **Parking tickets**: Traffic wardens
- **Examples**:
  - Handheld barcode scanners (warehouse)
  - PDA (Personal Digital Assistant)
  - Mobile POS devices
  - Delivery tracking devices (courier services)
- **Advantages**:
  - Mobility (data entry anywhere)
  - Real-time or batch data sync
  - Reduces paperwork
  - Immediate validation on screen
  - Increases efficiency
- **Disadvantages**:
  - Battery dependent
  - Expensive
  - Can be damaged
  - Requires training

---

## Summary Table: Input Devices Comparison

| Device | Type | Speed | Accuracy | Cost | Best For |
|--------|------|-------|----------|------|----------|
| Keyboard | Text entry | Medium | High (if skilled) | Low | Text-heavy work |
| Mouse | Pointing | Fast | High | Low | GUI navigation |
| Touch Screen | Direct input | Very Fast | Medium | High | Mobile devices |
| Light Pen | Pointing/Drawing | Fast | High | High | Design work |
| Barcode Reader | Scanning | Very Fast | Very High | Medium | Retail, inventory |
| Joystick | Gaming control | Fast | Medium | Medium | Gaming, simulation |
| MICR | Automatic | Very Fast | Very High | Very High | Cheque processing |
| OMR | Automatic | Very Fast | Very High | Medium | Exams, surveys |
| OCR | Automatic | Medium | Medium-High | Medium | Document scanning |
| Handheld Terminal | Mobile data | Fast | High | High | Field data collection |

---

## Quick Revision Points

✅ **Computer System**: Input → Process → Output  
✅ **5 Functional Units**: Input, Storage, ALU, Control, Output  
✅ **5 Generations**: Vacuum Tubes → Transistors → ICs → Microprocessors → AI  
✅ **3 Processing Types**: Batch, Online, Real-time  
✅ **MICR**: Cheque processing (magnetic ink)  
✅ **OMR**: Answer sheets (mark detection)  
✅ **OCR**: Text recognition (scanned documents)  
✅ **Touch Screen**: Capacitive (smartphones), Resistive (ATMs)  
✅ **Barcode**: 1D (linear), 2D (QR codes)  

---

**Good luck with your exam preparation! 🎯**
