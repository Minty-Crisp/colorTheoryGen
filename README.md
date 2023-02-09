# Color Theory Generator
Generate a color theory palette from a given color, random color within a color family or a random color from any family.

---
[View Examples](https://minty-crisp.github.io/)

---

Colors Generated :
- Base
- Complementary
- Split-Complementary
- Triadic
- Tetradic
- Analagous
- Monochrome (Coming Soon)

Color Families :
- Red
- Orange
- Yellow
- Lime
- Blue
- Cyan
- Magenta
- Maroon
- Olive
- Green
- Purple
- Teal
- Navy
- Silver (Not included in Random selection)
- Gray (Not included in Random selection)
- Black (Not included in Random selection)
- White (Not included in Random selection)

---

## How to Use :
Use the function `colorTheoryGen()` to return an object containing all colors generated from the provided parameters if any.

Use a Specific Color : (Currently only Hex colors supported)

`let newColor1 = colorTheoryGen('#00d3d3');`

Pick a Random Color from within a Color Family :

`let newColor1 = colorTheoryGen(false, 'red');`

Pick a Random Color from within any Color Family :

`let newColor1 = colorTheoryGen();`

Access the colors from the object with :
```
newColor1.base
newColor1.compl
newColor1.splitCompl[0]
newColor1.splitCompl[1]
newColor1.triadic[0]
newColor1.triadic[1]
newColor1.tetradic[0]
newColor1.tetradic[1]
newColor1.tetradic[2]
newColor1.analog[0]
newColor1.analog[1]
newColor1.analog[2]
```
---

### Future Improvements :

Accept rgb, hsl and text value inputs for the provided color.

Export monochrome color values.

---
### Minty Crisp ^-^ :watermelon: 

- If you want to see more work of mine, check out my other [repos](https://github.com/Minty-Crisp?tab=repositories) or my site [mintycrisp.com](https://mintycrisp.com).
- You can also check me out on a few other places like [dev.to](https://dev.to/mintycrisp) or where I spend most of my free time [reddit](https://www.reddit.com/user/Minty-Crisp/).
- I am available for Web & XR work if you are interested in hiring me or collaborating on future projects.
- You can reach me via socials or email : minty-crisp @ proton . me
- If you really enjoy my work and want to support me making more of these types of projects, you can help me out with a [kofi](https://ko-fi.com/mintycrisp) or just by sharing.