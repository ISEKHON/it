# UNIT 2: Computer Viruses, Internet, Output Devices & Word Processing

## 1. Computer Viruses

### What is a Computer Virus?
A **computer virus** is a malicious software program (malware) that can:
- **Self-replicate**: Makes copies of itself
- **Spread**: Transfers to other files/computers
- **Damage**: Corrupts data, slows system, steals information
- **Hide**: Conceals its presence

**Origin**: Named "virus" because it behaves like biological viruses - infects, replicates, and spreads.

### Characteristics of Viruses
1. **Self-replication**: Multiplies itself automatically
2. **Requires host**: Attaches to files/programs
3. **Needs execution**: Activates when infected file runs
4. **Spreads**: Through networks, USB drives, emails, downloads
5. **Harmful intent**: Designed to cause damage

### How Viruses Spread
- **Email attachments**: Infected files sent via email
- **USB/External drives**: Copying infected files
- **Downloads**: Downloading from untrusted websites
- **Pirated software**: Cracked/illegal software often contains viruses
- **Network sharing**: Shared folders on networks
- **Infected websites**: Drive-by downloads
- **Social engineering**: Tricking users to install malware

---

## 2. Types of Viruses

### A. Boot Sector Virus
- **Target**: Master Boot Record (MBR) of hard disk
- **Infection**: Activates when computer starts
- **Behavior**: 
  - Loads into memory before OS
  - Very difficult to remove
  - Prevents system booting
- **Spread**: Via infected bootable USB drives, CDs
- **Example**: Michelangelo, Stoned
- **Damage**: System won't boot, data corruption

### B. File Infector Virus (Program Virus)
- **Target**: Executable files (.exe, .com)
- **Infection**: Attaches to program files
- **Behavior**:
  - Activates when infected program runs
  - Spreads to other executables
  - Overwrites or appends to files
- **Spread**: Running infected applications
- **Example**: Cascade, Jerusalem
- **Damage**: Programs won't work, system crashes

### C. Macro Virus
- **Target**: Documents with macros (Word, Excel files)
- **Infection**: Uses macro programming language (VBA)
- **Behavior**:
  - Executes when document opens
  - Spreads to other documents
  - Can modify/delete content
- **Spread**: Email attachments, shared documents
- **Example**: Melissa, I Love You
- **Damage**: Document corruption, data theft

### D. Multipartite Virus
- **Target**: Both boot sector AND files
- **Infection**: Dual-mode attack
- **Behavior**:
  - Infects boot sector first
  - Then spreads to files
  - Very difficult to remove (must clean both)
- **Example**: Tequila, Invader
- **Damage**: Comprehensive system infection

### E. Polymorphic Virus
- **Special feature**: Changes its code/signature
- **Behavior**:
  - Modifies itself each time it replicates
  - Evades signature-based antivirus detection
  - Uses encryption to hide
- **Example**: Storm Worm, VirLock
- **Danger**: Hard to detect and remove

### F. Stealth Virus
- **Special feature**: Hides its presence
- **Behavior**:
  - Intercepts antivirus scans
  - Shows false information (fake file sizes)
  - Removes itself temporarily during scans
- **Example**: Frodo, Joshi
- **Danger**: Operates undetected for long periods

### G. Resident Virus (Memory Resident)
- **Target**: Computer's RAM
- **Behavior**:
  - Loads into memory at startup
  - Stays active even after host program closes
  - Infects files as they're accessed
- **Example**: CMJ, Randex
- **Removal**: Difficult (requires memory cleaning)

### H. Non-Resident Virus
- **Behavior**:
  - Does NOT stay in memory
  - Searches for targets when executed
  - Infects and then becomes inactive
- **Easier to remove** than resident viruses

### I. Other Malware Types (Related Concepts)

#### Worm
- **Difference from virus**: Self-contained (doesn't need host file)
- **Spread**: Automatically through networks
- **Behavior**: Consumes bandwidth, slows network
- **Example**: Conficker, Blaster
- **No user action needed** to spread

#### Trojan Horse
- **Disguise**: Appears as legitimate software
- **Behavior**: 
  - Doesn't replicate
  - Creates backdoor for hackers
  - Steals data, passwords
- **Example**: Zeus, Emotet
- **User unknowingly installs it**

#### Spyware
- **Purpose**: Secretly monitors user activity
- **Collects**: Browsing history, passwords, credit card info
- **Sends**: Data to third parties
- **Example**: Keyloggers, tracking cookies

#### Adware
- **Purpose**: Displays unwanted advertisements
- **Behavior**: Pop-ups, redirects to ad websites
- **Less harmful** but annoying and slows system

#### Ransomware
- **Purpose**: Encrypts user data
- **Demand**: Money (ransom) to decrypt
- **Example**: WannaCry, Petya
- **Very dangerous**: Can lock entire systems

---

## 3. Use of Antivirus Software

### What is Antivirus Software?
A program designed to **detect, prevent, and remove** viruses and malware from computers.

### How Antivirus Works

#### 1. Signature-Based Detection
- Maintains **virus signature database** (patterns/fingerprints)
- Scans files and compares with known signatures
- Identifies matching viruses
- **Limitation**: Can't detect new/unknown viruses

#### 2. Heuristic Detection
- Analyzes **behavior** of programs
- Looks for suspicious activities:
  - Modifying system files
  - Replicating itself
  - Accessing sensitive data
- Can detect **new/unknown** viruses
- **Drawback**: May flag legitimate programs (false positives)

#### 3. Behavioral Detection
- Monitors program behavior in real-time
- Blocks suspicious actions
- Sandboxing: Runs suspicious files in isolated environment

#### 4. Cloud-Based Detection
- Uses internet database for latest threat info
- Faster updates
- Less system resource usage

### Features of Antivirus Software

1. **Real-time scanning**: Monitors files as they're accessed
2. **Scheduled scanning**: Automatic periodic full scans
3. **Email protection**: Scans email attachments
4. **Web protection**: Blocks malicious websites
5. **Firewall**: Controls network traffic
6. **Automatic updates**: Downloads latest virus definitions
7. **Quarantine**: Isolates infected files
8. **Boot-time scanning**: Scans before OS loads (for boot viruses)
9. **USB scanning**: Auto-scans external drives
10. **Ransomware protection**: Prevents file encryption

### Popular Antivirus Software
- **Free**: Windows Defender, Avast, AVG, Avira
- **Paid**: Norton, McAfee, Kaspersky, Bitdefender, ESET

### Best Practices for Virus Protection

✅ **Install antivirus** and keep it updated  
✅ **Update OS regularly** (security patches)  
✅ **Don't open suspicious emails** or attachments  
✅ **Download from trusted sources** only  
✅ **Scan USB drives** before use  
✅ **Use strong passwords**  
✅ **Enable firewall**  
✅ **Regular backups** (offline/cloud)  
✅ **Avoid pirated software**  
✅ **Be cautious on public Wi-Fi**  

---

## 4. Internet Basics

### What is the Internet?
The **Internet** is a global network of interconnected computers that communicate using standard protocols (TCP/IP). It's a "network of networks" connecting millions of devices worldwide.

### Evolution of Internet
- **1960s**: ARPANET (first network by US Defense)
- **1970s**: TCP/IP protocol developed
- **1980s**: DNS (Domain Name System) introduced
- **1989**: World Wide Web (WWW) invented by Tim Berners-Lee
- **1990s**: Commercialization, browsers (Netscape, IE)
- **2000s**: Broadband, social media era
- **2010s**: Mobile internet, cloud computing
- **Present**: IoT, 5G, AI-driven internet

### Internet vs World Wide Web (WWW)
| Internet | World Wide Web |
|----------|---------------|
| Infrastructure (cables, routers) | Service running on internet |
| Network of networks | Collection of websites |
| Includes email, FTP, VoIP, etc. | Only web pages (HTTP/HTTPS) |
| Older (1960s) | Newer (1989) |

### How Internet Works
1. **ISP (Internet Service Provider)**: Provides internet connection (Jio, Airtel, BSNL)
2. **IP Address**: Unique identifier for each device (like a home address)
   - Example: 192.168.1.1 (IPv4) or 2001:0db8::1 (IPv6)
3. **Domain Name**: Human-readable address (google.com)
4. **DNS (Domain Name System)**: Converts domain names to IP addresses
5. **Protocols**: Rules for communication
   - **TCP/IP**: Data transmission
   - **HTTP/HTTPS**: Web pages
   - **FTP**: File transfer
   - **SMTP**: Email sending

**Example Flow**: Visiting www.google.com
```
You type URL → Browser asks DNS for IP → DNS returns 142.250.XXX.XXX 
→ Browser connects to Google's server → Server sends webpage → Browser displays
```

### Types of Internet Connections

#### 1. Dial-up
- Uses telephone line and modem
- Very slow (56 Kbps max)
- Blocks phone line when in use
- **Outdated**

#### 2. Broadband (DSL)
- Uses telephone line but doesn't block it
- Faster (512 Kbps - 100 Mbps)
- Always-on connection
- Common in early 2000s

#### 3. Cable Internet
- Uses TV cable infrastructure
- Fast (10-500 Mbps)
- Shared bandwidth (slows during peak hours)

#### 4. Fiber Optic (FTTH - Fiber To The Home)
- Uses light signals through glass fibers
- **Fastest** (100 Mbps - 1 Gbps+)
- Most reliable
- Expensive infrastructure

#### 5. Mobile/Cellular (4G/5G)
- Uses cellular network towers
- Portable (smartphones, dongles)
- **4G**: 10-100 Mbps
- **5G**: 1-10 Gbps (theoretical)

#### 6. Satellite
- Uses satellites in space
- Available in remote areas
- High latency (delay)
- Expensive

#### 7. Wi-Fi
- Wireless local network
- Connects devices within range (30-100 meters)
- Needs router connected to internet source

---

## 5. Uses and Applications of Internet

### 1. Communication
- **Email**: Gmail, Outlook (instant worldwide messaging)
- **Instant messaging**: WhatsApp, Telegram, Signal
- **Video calls**: Zoom, Google Meet, Skype, FaceTime
- **Social media**: Facebook, Instagram, Twitter, LinkedIn
- **Forums**: Reddit, Quora (community discussions)

### 2. Information and Research
- **Search engines**: Google, Bing, DuckDuckGo
- **Online encyclopedias**: Wikipedia
- **News websites**: BBC, CNN, news portals
- **Digital libraries**: Google Books, Project Gutenberg
- **Academic research**: Research papers, journals

### 3. Education (E-learning)
- **Online courses**: Coursera, Udemy, Khan Academy
- **Virtual classrooms**: Google Classroom, Microsoft Teams
- **Video tutorials**: YouTube, educational channels
- **E-books**: Kindle, PDF resources
- **Online exams**: Remote proctored tests

### 4. E-commerce (Online Shopping)
- **Shopping**: Amazon, Flipkart, eBay
- **Payment**: PayPal, UPI, net banking
- **Food delivery**: Swiggy, Zomato, Uber Eats
- **Cab services**: Uber, Ola
- **Hotel booking**: Booking.com, Airbnb

### 5. Entertainment
- **Streaming**: Netflix, Amazon Prime, Disney+
- **Music**: Spotify, YouTube Music, Apple Music
- **Gaming**: Online multiplayer, cloud gaming (Xbox Cloud, GeForce Now)
- **Social media**: TikTok, Instagram Reels

### 6. Banking and Finance
- **Net banking**: Online transactions
- **Mobile wallets**: Paytm, Google Pay, PhonePe
- **Stock trading**: Online trading apps
- **Cryptocurrency**: Bitcoin, digital currencies

### 7. Business
- **Remote work**: Work from home
- **Cloud services**: Google Drive, Dropbox (file storage)
- **Video conferencing**: Business meetings
- **Digital marketing**: Online advertisements
- **E-commerce**: Online stores

### 8. Government Services (E-Governance)
- **Online applications**: Passport, PAN card, driving license
- **Income tax**: Online filing
- **Aadhaar**: Digital identity
- **Digital payments**: BHIM, UPI
- **Certificates**: Birth, death certificates online

### 9. Healthcare
- **Telemedicine**: Online doctor consultations
- **Medicine delivery**: PharmEasy, Netmeds
- **Health apps**: Fitness tracking, diet planning
- **Medical records**: Online health portals

### 10. Navigation and Travel
- **GPS**: Google Maps, Waze
- **Travel booking**: MakeMyTrip, Goibibo
- **Flight tracking**: Real-time flight status
- **Hotel reviews**: TripAdvisor

---

## 6. Output Devices (Detailed)

### A. Monitor (Display)

#### What is a Monitor?
Primary output device that displays visual information (text, images, videos) in soft copy form.

#### Types of Monitors

##### 1. CRT (Cathode Ray Tube) - Old Technology
- **Technology**: Electron gun fires electrons at phosphor-coated screen
- **Appearance**: Bulky, heavy, box-shaped
- **Advantages**: 
  - Cheap
  - Good color accuracy
  - Wide viewing angles
- **Disadvantages**:
  - Large and heavy
  - High power consumption
  - Eye strain (flickering)
  - Low resolution
- **Status**: **Obsolete** (not used anymore)

##### 2. LCD (Liquid Crystal Display)
- **Technology**: Liquid crystals block/allow light from backlight
- **Types**:
  - **TN (Twisted Nematic)**: Fast response, poor viewing angles
  - **IPS (In-Plane Switching)**: Best color, wide viewing angles
  - **VA (Vertical Alignment)**: Good contrast
- **Advantages**:
  - Thin and lightweight
  - Less power consumption than CRT
  - No flickering
  - Affordable
- **Disadvantages**:
  - Limited viewing angles (TN panels)
  - Slower response time (motion blur)
- **Uses**: Desktop monitors, laptops, TVs

##### 3. LED (Light Emitting Diode)
- **Technology**: LCD with LED backlight (instead of fluorescent)
- **Types**:
  - **Edge-lit**: LEDs around edges (thinner)
  - **Full-array**: LEDs across panel (better brightness)
- **Advantages**:
  - Thinner than LCD
  - Better brightness and contrast
  - More energy-efficient
  - Longer lifespan
- **Uses**: Modern monitors, TVs, laptops

##### 4. OLED (Organic LED)
- **Technology**: Each pixel emits own light (no backlight needed)
- **Advantages**:
  - **Perfect blacks** (pixels turn off completely)
  - Infinite contrast ratio
  - Wide viewing angles
  - Faster response time
  - Thinner displays
- **Disadvantages**:
  - Expensive
  - Screen burn-in risk
  - Shorter lifespan
- **Uses**: High-end smartphones, TVs, laptops

##### 5. Touchscreen Monitors
- **Technology**: LCD/LED with touch layer
- **Uses**: POS systems, kiosks, tablets, all-in-one PCs

#### Monitor Specifications

1. **Resolution**: Number of pixels
   - HD: 1280×720
   - Full HD: 1920×1080
   - 2K: 2560×1440
   - 4K: 3840×2160
   - 8K: 7680×4320

2. **Screen Size**: Diagonal measurement in inches (19", 24", 27", 32")

3. **Refresh Rate**: How many times screen updates per second
   - 60 Hz (standard)
   - 120 Hz / 144 Hz (gaming)
   - Higher = smoother motion

4. **Response Time**: Pixel color change speed (1ms - 5ms)
   - Lower = less motion blur

5. **Aspect Ratio**: Width-to-height ratio
   - 16:9 (widescreen - common)
   - 21:9 (ultrawide)
   - 4:3 (old standard)

6. **Brightness**: Measured in nits/cd/m²
   - 250-350 nits (indoor)
   - 400+ nits (bright environments)

7. **Contrast Ratio**: Difference between darkest and brightest
   - 1000:1 (typical LCD)
   - Infinite (OLED)

---

### B. Printers

#### What is a Printer?
Output device that produces hard copy (physical/paper) output of digital documents.

#### Types of Printers

##### 1. Impact Printers (Old Technology)

**Dot Matrix Printer**
- **Technology**: 
  - Pins strike ink ribbon against paper
  - Creates characters from dot patterns
  - 9-pin or 24-pin print head
- **Mechanism**: Impact (physical contact)
- **Print quality**: Low (draft quality)
- **Speed**: Slow (50-500 cps - characters per second)
- **Noise**: Very noisy (clicking sound)
- **Cost**: Cheap (printer and running cost)
- **Uses**: 
  - Carbon copy printing (invoices, receipts)
  - Continuous form printing
  - Banking (passbook printing)
- **Advantages**:
  - Can print multiple copies (carbon paper)
  - Works with continuous paper
  - Very cheap per page
  - Durable
- **Disadvantages**:
  - Noisy
  - Poor print quality
  - Slow
  - Limited graphics capability
- **Status**: Still used in specific applications (bills, banks)

##### 2. Non-Impact Printers (Modern)

**A. Inkjet Printer**
- **Technology**:
  - Sprays tiny droplets of liquid ink onto paper
  - Uses ink cartridges (CMYK - Cyan, Magenta, Yellow, Black)
  - Thermal or piezoelectric mechanism
- **Mechanism**: Non-impact (no physical contact)
- **Print quality**: High (photo-quality possible)
- **Speed**: Medium (5-15 ppm - pages per minute)
- **Noise**: Quiet
- **Color**: Excellent color printing
- **Cost**:
  - Printer: Affordable
  - Running cost: High (expensive ink cartridges)
- **Uses**:
  - Home printing
  - Photo printing
  - Small office
  - Color documents
- **Advantages**:
  - Excellent print quality
  - Good color reproduction
  - Photo printing capability
  - Quiet operation
  - Affordable printer cost
- **Disadvantages**:
  - Expensive ink cartridges
  - Ink can dry out if not used regularly
  - Slow for bulk printing
  - Paper can smudge if wet
  - Not ideal for high-volume printing
- **Popular brands**: HP, Canon, Epson

**B. Laser Printer**
- **Technology**:
  - Uses laser beam to create image on drum
  - Toner (powder) sticks to charged areas
  - Heat fuses toner to paper
- **Process**:
  1. Laser charges drum
  2. Toner sticks to charged pattern
  3. Paper rolls over drum
  4. Heat fuses toner permanently
- **Print quality**: Very high (sharp text)
- **Speed**: Very fast (20-100 ppm)
- **Noise**: Quiet
- **Color**: Available (color laser more expensive)
- **Cost**:
  - Printer: Expensive
  - Running cost: Low (toner lasts long)
- **Uses**:
  - Office environments
  - High-volume printing
  - Professional documents
  - Schools, libraries
- **Advantages**:
  - Very fast printing
  - Low cost per page
  - Sharp, professional quality
  - Toner doesn't dry out
  - Ideal for bulk printing
  - Water-resistant prints
- **Disadvantages**:
  - Expensive initial cost
  - Large and heavy
  - High power consumption
  - Warm-up time needed
  - Color laser very expensive
- **Popular brands**: HP LaserJet, Canon, Brother, Xerox

**C. Thermal Printer**
- **Technology**: Uses heat to print on special heat-sensitive paper
- **Mechanism**: Heated pins darken thermal paper
- **Print quality**: Moderate
- **Speed**: Fast
- **Noise**: Very quiet
- **Uses**:
  - Receipt printing (shops, ATMs)
  - Barcode labels
  - Tickets (parking, movie)
  - Fax machines
- **Advantages**:
  - Very fast
  - Quiet
  - No ink/toner needed
  - Compact size
- **Disadvantages**:
  - Requires special paper (expensive)
  - Prints fade over time
  - Heat-sensitive (can't be stored in hot places)

##### 3. Specialized Printers

**3D Printer**
- **Technology**: Builds 3D objects layer by layer using materials (plastic, resin, metal)
- **Uses**: Prototyping, manufacturing, medical implants, custom parts

---

### C. Plotters

#### What is a Plotter?
Specialized output device for printing **large-format graphics** with high precision. Used for engineering and architectural drawings.

#### How Plotters Work
- Uses pens, pencils, or markers
- Draws continuous lines (not dots like printers)
- Can move on X and Y axes
- Produces vector graphics

#### Types of Plotters

##### 1. Flatbed Plotter
- **Design**: Paper lies flat on table
- **Mechanism**: Pen moves in X and Y directions
- **Size**: Can plot very large sheets
- **Accuracy**: Very high
- **Speed**: Slow
- **Uses**: Architecture, engineering, large maps

##### 2. Drum Plotter
- **Design**: Paper wrapped around rotating drum
- **Mechanism**: 
  - Drum rotates (Y-axis movement)
  - Pen moves left-right (X-axis)
- **Size**: Can handle long continuous plots
- **Speed**: Faster than flatbed
- **Uses**: Long charts, seismic data, continuous designs

#### Uses of Plotters
- Architectural blueprints
- Engineering CAD drawings
- City planning maps
- Circuit board designs
- Advertising banners
- Fashion/textile design patterns

#### Plotter vs Printer
| Feature | Plotter | Printer |
|---------|---------|---------|
| Purpose | Large graphics, drawings | Documents, photos |
| Technology | Pens draw continuous lines | Dots (pixels) |
| Size | Very large format | Standard paper sizes |
| Quality | Vector graphics (scalable) | Raster (pixelated if zoomed) |
| Speed | Slow | Fast |
| Cost | Very expensive | Affordable |
| Uses | Engineering, architecture | General purpose |

---

### D. Voice Response Units (Audio Output)

#### What are Voice Response Units?
Output devices that convert digital data into **spoken words** (audio output).

#### Types

##### 1. Speakers
- **Function**: Convert electrical signals to sound waves
- **Types**:
  - Desktop speakers (2.0, 2.1 with subwoofer)
  - 5.1/7.1 surround sound
  - Bluetooth speakers
  - Studio monitors
- **Uses**:
  - Music playback
  - Movie audio
  - Gaming
  - Video calls
  - System alerts

##### 2. Headphones/Earphones
- **Function**: Personal audio output
- **Types**:
  - Wired/wireless
  - Over-ear, on-ear, in-ear
  - Noise-canceling
- **Uses**:
  - Private listening
  - Gaming communication
  - Phone calls
  - Music

##### 3. Interactive Voice Response (IVR) Systems
- **Function**: Automated phone systems that speak responses
- **Technology**:
  - Text-to-Speech (TTS) conversion
  - Pre-recorded messages
  - Menu-driven interaction
- **How it works**:
  1. User calls helpline
  2. System plays voice menu ("Press 1 for..., Press 2 for...")
  3. User selects option (keypad)
  4. System responds with voice
- **Uses**:
  - **Customer service**: Bank helplines, telecom support
  - **Information systems**: Railway enquiry, flight status
  - **Automated attendants**: Office phone systems
  - **Surveys**: Automated feedback collection
- **Examples**:
  - "Your account balance is rupees five thousand"
  - "Press 1 for English, Press 2 for Hindi"
  - "Your train is running 30 minutes late"

##### 4. Text-to-Speech (TTS) Systems
- **Function**: Converts written text to spoken words
- **Uses**:
  - Screen readers for visually impaired
  - E-book narration
  - GPS navigation (turn-by-turn directions)
  - Announcements (airports, railway stations)
  - Virtual assistants (Siri, Google Assistant, Alexa)
- **Examples**:
  - Google Maps: "Turn left after 200 meters"
  - Screen reader: Reads web pages aloud

#### Applications of Voice Output
✅ **Accessibility**: Helps blind/visually impaired users  
✅ **Hands-free operation**: GPS while driving  
✅ **Customer service**: 24/7 automated responses  
✅ **Multilingual support**: Can speak multiple languages  
✅ **Cost-effective**: Reduces need for human operators  

---

## 7. Word Processor (Detailed Guide)

### What is a Word Processor?
Software application for creating, editing, formatting, and printing text documents. It's the digital replacement for typewriters.

**Popular Word Processors:**
- Microsoft Word (most popular)
- Google Docs (online, free)
- LibreOffice Writer (free, open-source)
- Apache OpenOffice Writer (free)
- Apple Pages (Mac)

---

### A. Overview and Basic Operations

#### Creating a New Document
- **MS Word**: File → New → Blank Document
- **Shortcut**: Ctrl + N
- **Google Docs**: Click "+" or "Blank"

#### Saving a Document
- **First time save**: File → Save As
- **Shortcut**: Ctrl + S
- **Choose location**: Computer, OneDrive, Google Drive
- **File formats**:
  - .docx (Word 2007+)
  - .doc (older Word)
  - .pdf (non-editable)
  - .txt (plain text)
  - .rtf (Rich Text Format)
  - .odt (OpenDocument)

#### Opening an Existing Document
- File → Open
- **Shortcut**: Ctrl + O
- Browse and select file
- **Recent documents**: Quick access to last opened files

#### Importing Files
- **Insert content from another file**: Insert → Object → Text from File
- **Copy-paste**: From other documents
- **Drag and drop**: Files into document
- **Uses**: Combine multiple documents, reuse content

#### Exporting Files
- **Save in different format**: File → Save As → Choose format
- **Export to PDF**: File → Export → Create PDF
- **Send via email**: File → Share → Email
- **Uses**: Share with users who don't have Word, create non-editable versions

#### Inserting Files
- **Pictures**: Insert → Pictures → From computer/online
- **Tables**: Insert → Table
- **Charts**: Insert → Chart
- **Videos**: Insert → Online Video (embedded)
- **Audio**: Insert → Audio (PowerPoint feature, limited in Word)
- **Shapes**: Insert → Shapes
- **Hyperlinks**: Insert → Link

---

### B. Formatting Pages

#### Page Setup
- **Access**: Layout → Page Setup
- **Margins**: Distance between text and page edge
  - Normal: 1" all sides
  - Narrow: 0.5" all sides
  - Wide: 2" left/right, 1" top/bottom
  - Custom: Set your own
- **Orientation**:
  - Portrait: Vertical (default)
  - Landscape: Horizontal
- **Paper size**:
  - A4 (21×29.7 cm) - standard
  - Letter (8.5×11 inches)
  - Legal, A3, Custom

#### Page Breaks
- **Purpose**: Force new page to start
- **Insert**: Insert → Page Break
- **Shortcut**: Ctrl + Enter
- **Uses**: Start new chapter, separate sections

#### Page Numbers
- **Insert**: Insert → Page Number
- **Positions**:
  - Top of page (header)
  - Bottom of page (footer)
  - Page margins (sides)
- **Formats**:
  - 1, 2, 3... (Arabic)
  - i, ii, iii... (Roman lowercase)
  - I, II, III... (Roman uppercase)
  - a, b, c... (Alphabetic)
- **Start from specific number**: Format Page Numbers → Start at: 5

#### Page Borders
- Design → Page Borders
- Choose style, color, width
- Apply to: Whole document, current section, first page only

---

### C. Formatting Paragraphs and Sections

#### Paragraph Formatting
- **Access**: Home tab or right-click → Paragraph

##### Alignment
- **Left align**: Ctrl + L (default)
- **Center**: Ctrl + E (titles, headings)
- **Right align**: Ctrl + R (dates, addresses)
- **Justify**: Ctrl + J (both edges aligned - professional)

##### Line Spacing
- Space between lines of text
- **Options**:
  - Single (1.0)
  - 1.15 (default in Word)
  - 1.5
  - Double (2.0)
  - Custom
- **Shortcut**: Ctrl + 1 (single), Ctrl + 2 (double), Ctrl + 5 (1.5)
- **Before/After paragraph spacing**: Add extra space above/below paragraphs

##### Indentation
- **First line indent**: First line starts ahead
  - Used in essays, stories
  - Set in Paragraph settings
- **Hanging indent**: First line normal, rest indented
  - Used in references, bibliographies
- **Left indent**: Entire paragraph moved right
- **Right indent**: Entire paragraph moved left
- **Measurement**: Usually in inches or cm

#### Indents and Outdents

**Indent**: Move text away from margin (to the right)
- **Increase indent**: Home → Increase Indent (or Tab key)
- **Decrease indent**: Home → Decrease Indent (or Shift + Tab)
- **Uses**: Hierarchical lists, nested content, quotations

**Outdent** (Negative Indent): Move text toward/beyond margin (to the left)
- Pull text back to margin
- Create hanging indents
- **Uses**: Special formatting effects

---

### D. Creating Lists and Numbering

#### Bulleted Lists
- **Purpose**: Unordered items (order doesn't matter)
- **Insert**: Home → Bullets
- **Shortcut**: Type * and space, then text
- **Bullet styles**:
  - Solid circle •
  - Hollow circle ○
  - Square ■
  - Checkmark ✓
  - Custom symbols
- **Uses**: Features, items, non-sequential points

#### Numbered Lists
- **Purpose**: Ordered items (sequence matters)
- **Insert**: Home → Numbering
- **Shortcut**: Type 1. and space, then text
- **Number styles**:
  - 1, 2, 3... (Arabic)
  - I, II, III... (Roman uppercase)
  - i, ii, iii... (Roman lowercase)
  - a, b, c... (lowercase letters)
  - A, B, C... (uppercase letters)
- **Uses**: Steps, procedures, rankings, instructions

#### Multilevel Lists
- **Purpose**: Nested hierarchical lists (outlines)
- **Insert**: Home → Multilevel List
- **Example**:
  ```
  1. Main topic
     1.1. Subtopic
     1.2. Subtopic
        1.2.1. Sub-subtopic
  2. Next main topic
  ```
- **Indent/Outdent**: Tab (go deeper), Shift+Tab (go up level)
- **Uses**: Outlines, legal documents, complex hierarchies

#### Customizing Lists
- Right-click list → Adjust List Indents
- Change bullet/number style
- Set indentation and spacing
- **Restart numbering**: Right-click → Restart at 1
- **Continue numbering**: Continue from previous list

---

### E. Headings, Styles, Fonts

#### Headings
- **Purpose**: Organize document structure, create Table of Contents
- **Levels**: Heading 1, Heading 2, Heading 3... Heading 9
  - **Heading 1**: Main chapters
  - **Heading 2**: Sections
  - **Heading 3**: Subsections
- **Apply**: Home → Styles → Heading 1/2/3
- **Shortcut**: Ctrl + Alt + 1/2/3
- **Benefits**:
  - Creates document outline
  - Generates automatic Table of Contents
  - Easy navigation
  - Consistent formatting

#### Styles
- **Definition**: Pre-defined formatting combinations (font, size, color, spacing)
- **Types**:
  - Normal (body text)
  - Heading 1, 2, 3...
  - Title
  - Subtitle
  - Quote
  - Emphasis
  - Strong
- **Apply**: Home → Styles gallery
- **Modify style**: Right-click style → Modify
  - Change font, size, color, spacing
  - Updates all text using that style
- **Create new style**: Save custom formatting combination
- **Benefits**:
  - Consistency throughout document
  - Quick formatting changes
  - Professional appearance

#### Fonts

**Font (Typeface)**: Style of letters
- **Common fonts**:
  - **Arial**: Clean, modern (sans-serif)
  - **Times New Roman**: Traditional, formal (serif)
  - **Calibri**: Default in Word (sans-serif)
  - **Verdana**: Web-friendly, readable
  - **Georgia**: Elegant serif for screen reading
  - **Comic Sans**: Casual (avoid in formal documents!)

**Font Categories**:
- **Serif**: Has decorative strokes (Times, Georgia) - traditional, print
- **Sans-serif**: No decorative strokes (Arial, Calibri) - modern, screen
- **Monospace**: Equal width (Courier) - coding, typewriter effect

**Font Size**:
- Measured in **points (pt)**
- **Common sizes**:
  - 8-10 pt: Fine print, footnotes
  - 11-12 pt: Body text (standard)
  - 14-18 pt: Subheadings
  - 20-28 pt: Headings
  - 36+ pt: Titles, posters
- **Shortcut**: Ctrl + ] (increase), Ctrl + [ (decrease)

**Font Formatting**:
- **Bold**: Ctrl + B (emphasis)
- **Italic**: Ctrl + I (emphasis, book titles)
- **Underline**: Ctrl + U (headings, links)
- **Strikethrough**: Draw line through text (deleted items)
- **Subscript**: Below baseline (H₂O)
- **Superscript**: Above baseline (x²)
- **Font color**: Home → Font Color
- **Highlight**: Home → Text Highlight Color (mark important text)
- **Text effects**: Shadow, glow, reflection, outline

---

### F. Editing, Positioning, and Viewing Text

#### Editing Operations

**Select Text**:
- **Mouse**: Click and drag
- **Keyboard**: Shift + Arrow keys
- **Word**: Double-click
- **Sentence**: Ctrl + click
- **Paragraph**: Triple-click
- **All**: Ctrl + A

**Cut, Copy, Paste**:
- **Cut**: Ctrl + X (remove and copy)
- **Copy**: Ctrl + C (duplicate)
- **Paste**: Ctrl + V (insert)
- **Paste Special**: Paste without formatting

**Undo and Redo**:
- **Undo**: Ctrl + Z (reverse last action)
- **Redo**: Ctrl + Y (restore undone action)
- **Multiple undo**: Repeat Ctrl + Z

**Delete**:
- **Delete key**: Remove character to right
- **Backspace**: Remove character to left
- **Ctrl + Delete**: Delete word to right
- **Ctrl + Backspace**: Delete word to left

#### Find and Replace

**Find** (Search for text):
- **Open**: Ctrl + F
- **Navigation pane** appears
- Type search term
- Results highlighted
- **Advanced**: Match case, whole words only, wildcards

**Replace** (Find and replace text):
- **Open**: Ctrl + H
- **Find what**: Text to search
- **Replace with**: New text
- **Options**:
  - **Replace**: Change one instance
  - **Replace All**: Change all instances
  - **Match case**: Respect uppercase/lowercase
- **Uses**:
  - Fix repeated typos
  - Change names throughout document
  - Update terminology
  - Format consistency

**Go To**:
- **Shortcut**: Ctrl + G
- Jump to specific page, section, line, bookmark

#### Positioning Text

**Vertical Alignment** (Page Layout → Page Setup → Layout):
- **Top**: Default (starts at top)
- **Center**: Centered vertically (title pages)
- **Justified**: Spread evenly top to bottom
- **Bottom**: Text at bottom of page

**Text Wrapping** (for images/shapes):
- **In Line with Text**: Image acts like character
- **Square**: Text wraps around rectangle
- **Tight**: Text wraps close to image
- **Through**: Text flows through transparent areas
- **Top and Bottom**: Text above and below only
- **Behind Text**: Image in background
- **In Front of Text**: Image covers text

#### Viewing Modes

**View Tab** options:
1. **Print Layout**: Default, shows pages as they'll print
2. **Read Mode**: Full-screen reading (no toolbars)
3. **Web Layout**: How document looks on web
4. **Outline**: Hierarchical structure view (headings collapsed)
5. **Draft**: Simple view (faster, no graphics)

**Zoom**:
- View → Zoom → 100%, 125%, 150%, 200%
- **Fit to window**: Shows entire page
- **Zoom slider**: Bottom-right corner

**Split Screen**:
- View → Split
- View two parts of same document simultaneously
- Good for comparing sections

**Navigation Pane**:
- View → Navigation Pane (or Ctrl + F)
- Shows document outline
- Headings clickable for quick navigation

---

### G. Inserting Elements

#### Bookmarks
- **Purpose**: Mark specific locations in document for quick access
- **Insert**: Insert → Bookmark → Name it
- **Go to bookmark**: Ctrl + G → Bookmark → Select name
- **Uses**:
  - Large documents (quick navigation)
  - Create hyperlinks to specific sections
  - Reference points

#### Symbols
- **Insert**: Insert → Symbol
- **Common symbols**:
  - © (copyright)
  - ® (registered trademark)
  - ™ (trademark)
  - ° (degree)
  - ½ ¼ ¾ (fractions)
  - α β γ (Greek letters)
  - ∞ ≈ ≠ (mathematical)
  - ♥ ♦ ♣ ♠ (special)
- **Shortcut**: Alt + code (e.g., Alt + 0169 for ©)
- **Equation editor**: Insert → Equation (for complex math)

#### Dates
- **Insert**: Insert → Date and Time
- **Formats**:
  - 12/07/2025
  - December 7, 2025
  - 07-Dec-25
  - Friday, December 7, 2025
- **Update automatically**: Check box to update on opening
- **Shortcut**: Alt + Shift + D (date), Alt + Shift + T (time)

---

### H. Using Tabs and Tables

#### Tabs
- **Purpose**: Align text at specific positions (like columns)
- **Types of tab stops**:
  1. **Left tab**: Text aligns left from tab
  2. **Center tab**: Text centers on tab
  3. **Right tab**: Text aligns right to tab
  4. **Decimal tab**: Numbers align on decimal point
  5. **Bar tab**: Vertical line at tab position

- **Set tabs**:
  - Click ruler where you want tab
  - Or: Home → Paragraph → Tabs (precise)
- **Use tab**: Press Tab key
- **Clear tab**: Drag off ruler

**Uses**: 
- Create simple columns
- Align prices in menus
- Format resumes

#### Tables

**Insert Table**:
- **Method 1**: Insert → Table → Drag grid (e.g., 3×4)
- **Method 2**: Insert → Table → Insert Table → Specify rows/columns
- **Method 3**: Draw Table tool (custom cells)

**Table Components**:
- **Cell**: Individual box
- **Row**: Horizontal line of cells
- **Column**: Vertical line of cells
- **Border**: Lines around cells
- **Gridlines**: Non-printing guides

**Table Operations**:
- **Add row**: Right-click → Insert → Insert Rows Above/Below
- **Add column**: Right-click → Insert → Insert Columns Left/Right
- **Delete row/column**: Right-click → Delete
- **Merge cells**: Select cells → Right-click → Merge Cells
- **Split cells**: Right-click → Split Cells
- **Distribute rows evenly**: Make all rows same height
- **Distribute columns evenly**: Make all columns same width

**Table Formatting**:
- **Table Design tab**:
  - Table Styles (pre-designed looks)
  - Shading (cell background color)
  - Border styles (line thickness, color)
  - Header row (first row formatted differently)
  - Banded rows (alternating colors)
- **Layout tab**:
  - Cell size (height/width)
  - Text alignment (top/middle/bottom)
  - Text direction (rotate text)
  - Cell margins (padding inside cells)

**Convert**:
- **Text to Table**: Select text → Insert → Table → Convert Text to Table
  - Separates at tabs, commas, or paragraphs
- **Table to Text**: Select table → Layout → Convert to Text

**Uses**:
- Data organization
- Comparisons (features vs. products)
- Schedules, timetables
- Price lists
- Resumes, CVs

---

### I. Header, Footer, and Printing

#### Header
- **Definition**: Top margin area (repeats on every page)
- **Insert**: Insert → Header → Choose style
- **Double-click**: Top of page to edit header
- **Contents**:
  - Document title
  - Chapter name
  - Page numbers
  - Date
  - Author name
  - Company logo

#### Footer
- **Definition**: Bottom margin area (repeats on every page)
- **Insert**: Insert → Footer → Choose style
- **Double-click**: Bottom of page to edit footer
- **Contents**:
  - Page numbers ("Page 1 of 10")
  - Copyright notice
  - Date
  - Confidentiality notice

**Header/Footer Options**:
- **Different first page**: Unique header/footer for page 1 (title pages)
- **Different odd/even pages**: Books (chapter on left, title on right)
- **Close**: Double-click document body or click "Close Header and Footer"

#### Printing

**Print Preview**:
- File → Print
- **Shortcut**: Ctrl + P
- Shows how document will print
- Adjust before printing

**Print Settings**:
1. **Printer**: Select from available printers
2. **Pages**:
   - All pages
   - Current page
   - Custom range (e.g., 1-5, 8, 10-12)
3. **Copies**: How many copies to print
4. **Collation**: 
   - Collated: 1,2,3,1,2,3 (complete sets)
   - Uncollated: 1,1,2,2,3,3
5. **Orientation**: Portrait / Landscape
6. **Paper size**: A4, Letter, Legal, etc.
7. **Margins**: Normal, Narrow, Wide
8. **Pages per sheet**: 1, 2, 4, 6, 8, 16 (save paper)
9. **Print on both sides** (Duplex):
   - Flip on long edge (book-style)
   - Flip on short edge (notepad-style)
   - Manual duplex (print, flip, reload)
10. **Color**: Color or Black & White

**Print Shortcuts**:
- Ctrl + P: Open print dialog
- Ctrl + Shift + F12: Print immediately with default settings

**Print to PDF**:
- Select "Microsoft Print to PDF" as printer
- Saves as PDF instead of printing
- **Uses**: Email documents, preserve formatting

---

## Quick Revision Summary

### Viruses
✅ **Self-replicating malicious software**  
✅ **Types**: Boot sector, File infector, Macro, Multipartite, Polymorphic, Stealth  
✅ **Antivirus**: Signature-based + Heuristic detection  
✅ **Protection**: Update software, scan regularly, avoid suspicious files  

### Internet
✅ **Global network of networks** using TCP/IP  
✅ **WWW**: Collection of websites (part of internet)  
✅ **Connections**: Dial-up → DSL → Fiber → 4G/5G  
✅ **Uses**: Communication, E-learning, E-commerce, Entertainment  

### Output Devices
✅ **Monitor**: CRT → LCD → LED → OLED  
✅ **Printers**: Dot Matrix (impact), Inkjet (color, photo), Laser (fast, office)  
✅ **Plotter**: Large-format technical drawings  
✅ **Voice**: Speakers, IVR systems, Text-to-Speech  

### Word Processing
✅ **Basic**: Create, Save (Ctrl+S), Open (Ctrl+O)  
✅ **Formatting**: Fonts, alignment, line spacing, indentation  
✅ **Lists**: Bullets (unordered), Numbering (ordered), Multilevel  
✅ **Headings**: Structure for Table of Contents  
✅ **Find/Replace**: Ctrl+F / Ctrl+H  
✅ **Tables**: Insert, format, merge cells  
✅ **Header/Footer**: Repeating content on all pages  
✅ **Print**: Ctrl+P, preview before printing  

---

**Study tip**: Practice Word features hands-on! Open Word and try each feature while studying. Good luck! 📚**
