# Universal Vintage Computer Power Supply
Idea for a "universal" power supply, either internal external, for different systems that require multiple input voltages (like 8080-based systems, or the BBC Model B).<br>

It's nothing groundbreaking, unique or even clever - it just uses off-the-shelf integrated components to generate the additional voltages.<br>

Expects regulated +12VDC input (rated at 5A).<br>

Passes through the +12VDC (max. 400mA) and additionally outputs:
- Regulated +5VDC (max. 4A)
- Regulated -12VDC (max. 80mA)
- Regulated -5VDC (max. 500mA)

If the additional voltages are not required then they can be excluded from the build.<br>

Prevents reverse-polarity source input with a MOSFET (can be excluded if not required).<br>

The PCB measures 70x50mm and has M3 mounting holes in the corners (offset 42 & 62mm).<br>

![3D image of PCB](/Universal_Modern_PSU_3D.png)
