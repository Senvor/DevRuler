<div align="center">

# DevRuler

**A custom PCB ruler for developers to show off their identity without saying a word.**



![Hackatime](https://hackatime.hackclub.com/api/v1/badge/U0B4TE3MN1G/Senvor/DevRuler)



<img src="assets/final-front.jpg" alt="DevRuler finished PCB" width="700" />

</div>

---

## What exactly is it?

It's an everyday-use ruler designed specifically for developers. I packed it with some cool stuff:

- **Hardware footprints** for quick sizing and idk, all the footprints are random.
- **Daily use commands** for the moments when your brain completely blanks on basic commands.
- **Basic SI unit conversions** so you never have to Google them again.
- Sweet branding from [Hack Club](https://hackclub.com/) and their awesome hardware program, [Forge](https://forge.hackclub.com/)!

## Why I built it

I have always loved watching hardware videos on YouTube, and one day I found a video showcasing a PCB ruler. I was instantly obsessed with the idea and decided to make my own custom PCB Ruler.

I started searching for a good Hack Club program to make it in, and after a while I found Forge, a really cool hardware-only HC program, and started working on my project.

## The PCB Design

I designed the entire board from scratch using **KiCad**.

<div align="center">
  <img src="assets/PCB.png" alt="PCB Design in KiCad" width="700" />
  <br/>
  <i>A look at the raw KiCad layout.</i>
</div>

## Fabrication (JLCPCB)

Here's the final manufacturing quote and preview from JLCPCB before it became reality:

<div align="center">
  <img width="1275" height="571" alt="JLCPCB quote" src="https://github.com/user-attachments/assets/8a448917-cd71-45b3-ac50-17768dd789c3" />
</div>

## It arrived!

The boards showed up from JLCPCB and they look great.

<div align="center">
  <img src="assets/unboxing.jpg" alt="Unboxing the DevRuler PCBs" width="600" />
  <br/>
  <i>Fresh out of the package.</i>
</div>

<br/>

| Front | Back |
|:---:|:---:|
| <img src="assets/final-front.jpg" alt="Front of DevRuler" width="350" /> | <img src="assets/final-back.jpg" alt="Back of DevRuler" width="350" /> |

<div align="center">
  <img src="assets/in-use.jpg" alt="DevRuler next to a laptop" width="600" />
  <br/>
  <i>Sitting on my desk, measuring things it was never meant to measure.</i>
</div>

## Bill Of Materials

| Category | Item Name | Description | Vendor | Quantity | Unit Price (USD) | Total Price (USD) |
|---|---|---|---|---:|---:|---:|
| PCB | DevRuler | The coolest Ruler OAT | JLCPCB | 5 | $9.99 | $34.39 |

## Repository

- `pcb/`: KiCad project files
- `assets/`: images used in this README
- `BOM.csv`: bill of materials
- `output files/`: fabrication outputs

## License

MIT, see [LICENSE](LICENSE).
