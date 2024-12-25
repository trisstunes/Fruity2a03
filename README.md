# Fruity 2a03
A Sytrus preset that emulates the NES soundchip's Pulse Channels

## Basics

### Tabs 
![image](https://github.com/user-attachments/assets/2fe27975-15d2-44c1-85e8-751f12bffbc1)

Sytrus features 11 tabs with various settings  
But we're only going to cover a few for this patch

## Main

Most of this patch's functions (such as **Volume Envelope**, **Pitch Modulation**, and **Pulse Width Modulation**) can be controlled on the **Main** tab.

### Volume and LFO
Here you can control the **master volume** and **pitch**:

![Main Vol](https://github.com/user-attachments/assets/4b637119-b0b4-4ba0-bd14-9c73cb3d5ca0)

Adjusting **LFO** will introduce **pitch modulation** (aka _vibrato_). 

You can further adjust **pitch modulation** settings in the [**OP 1 tab**](#pitch-lfo)

### ADSR
Use **Main ADSR** for volume envelope

![Main ADSR](https://github.com/user-attachments/assets/cb2433ad-f64c-47f5-a737-c0d158b3b6c4)

### Duty Cycle
The NES had two pulse channels with variable duty cycle, which changed the timbre of the voice.  

**Mod X** controls duty cycle (12.5%, 25%, 50%, 75%)

![Duty](https://github.com/user-attachments/assets/8b8918e5-aca2-4d3d-87b7-6de2d45a0341)

## Advanced
### OP 1 Tab
![image](https://github.com/user-attachments/assets/a10bbf9b-a2c0-4df3-91ae-146e0ab54c9c)

For more granular control of various parameters, we can move onto the **OP 1** tab

![image](https://github.com/user-attachments/assets/51e45130-a42a-4737-8085-c0c3c506f28a)

### Pitch LFO

Under the OP 1 tab, there are several more adjustments you can make.  
If you change too much here, this patch will stray from the classic NES bleeps and bloops very quickly.

Under the Pitch editor pannel, you can further adjust the **pitch modulation settings**.  
I recommend sticking to Speed control in the bottom left corner, which will change how fast your vibrato will be.


![OP1 LFO](https://github.com/user-attachments/assets/ba130bec-a72c-4f59-9219-8bebde2c259c)

In order to hear this change, you must adjust the [**LFO setting** on the **Main Tab**](#volume-and-lfo)

### Pitch Envelopes

Under the Envelope tab, you can create **pitch envelopes**  
The default ADSR points can yield some fun sound effects, but you can make even more cool things by creating your own custom envelopes.

![Pitch Env](https://github.com/user-attachments/assets/f85e672d-0649-435b-8475-6fab0218b269)
