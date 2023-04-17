# AR One Sans Font Family
_A Typeface for Augmented Reality and User Interfaces_

### Overview
The AR One Sans font family is designed for use in augmented reality environments and user interfaces. Its low contrast, generous spacing, and robust shapes make it highly legible and easy to read in busy backgrounds. The font also has specific optical weights duplexed (uni-width) for high and low-resolution displays to avoid text reflow and enhance the user experience across devices. The functionality of the font has been extensively tested to ensure a smooth and comfortable reading experience, even in longer texts.

### Context

The rapid evolution of technology has prompted the type industry to consistently produce typefaces that are optimized for various environments and devices. AR One is a font family that is specifically designed to support augmented and virtual reality environments, helping a wide range of users overcome technical limitations by providing a better reading experience. The font is not limited to AR and VR applications, and can also be used in contexts such as automobile dashboards, signage, and mobile applications.

### Design Features

- The design of the letterforms in AR One is based on research and testing on a range of devices, from high-end headsets to low-resolution smartphone screens. This ensures that the font is able to withstand resolution and response time limitations, providing a consistently legible and user-friendly experience.
- The typeface uses the "Marionette formula," a design concept introduced by William A. Dwiggins. This formula substitutes straight lines for curves in certain letterforms, creating the illusion of more graceful curvature than is possible with actual curves. To achieve this effect, the typeface's cuts utilize the excess glow around the text to produce a smooth curve, resulting in letters with a more traditional shape, rather than those composed entirely of straight lines.
- The design is tested to improve the reading experience even in longer paragraphs, beyond small UI text strings.
- The letterforms are highly legible and have distinct shapes to avoid confusion between commonly misrecognized letters.
- The spacing and width of letters are optimized for negative polarity (light text on dark background) and angular distortion.
- The shapes are compatible with anti-interference techniques, which are recommended by researchers for better readability in AR environments.
- Specific design features have been added to reduce the effect of halation, and pixel loss in the lower resolution which causes the stroke ends to appear rounded.

### Generational Scalability
The scalability of the AR One font family across different resolutions makes it an ideal choice not just for current-generation headsets, but also for future headsets. The font is also developed with a complex script in mind and has the ability to accommodate a wider design vocabulary (coming soon).

## Variable Axes

| Axis | Tag | Range | Default | Description |
| --- | --- | --- | --- | --- |
| Augmented Reality Retinal Resolution | ARRR | 10 to 60 | 10 | Optimises the letter shapes and design to aid legibility based on the retinal resolution (PPD, pixel per degree) of devices. |
| Weight | wght | 400 to 700 | 400 | Regular to Bold |

### Augmented Reality Retinal Resolution Axis

**Description:** Resolution-specific enhancements in AR/VR typefaces optimize text without changing the width of the letters, maintaining consistent spacing and kerning, and preserving layout and line breaks. This ensures a consistent design and layout across different resolutions, making designs accessible and easy to read, regardless of the headset's resolution.

Some of the adjustments in `ARRR` include: 

1. Addition of flaring at stroke ends to reduce the rounding effect at the ends due to missing pixels (in low resolution). It optimizes the shape of letters minimizing the rounding effect that can occur with rectangular strokes, making them appear more like rounded rectangles.
2. Light traps to reduce excess glow at the intersection of strokes.
3. Large x-height for a lower resolution to increase the counters and apertures and balance the negative space inside the letters due to flaring.

**Scale interpretation:** In the proposed resolution-specific adjustments for AR/VR typefaces, the lower value of the axis corresponds to the PPD of low-resolution headsets, while the upper value corresponds to 60 PPD, which is considered retina resolution. Beyond this point, the effect of adjustments on legibility and readability becomes negligible. Therefore, by limiting the adjustments to this range, designers can optimize the legibility and readability of their typefaces for a wide range of headsets while minimizing the amount of adjustment work required.

**Recommended Use:** Is to map the `ARRR` to the resolution of headsets and render the typefaces according to that.



### Charcter Set


### OpenType Features



## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL
