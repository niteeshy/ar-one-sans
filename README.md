# AR One Sans Font Family 
_A Typeface for Augmented Reality and User Interfaces_

Note: This project is set to launch soon. Hence more details will be availble then.

<img width="1600" alt="Cover" src="https://user-images.githubusercontent.com/26871553/233336317-b7de7901-2ff2-45a3-98c6-6362985891cd.png">


### Overview
The AR One Sans type family is for use in augmented reality environments and user interfaces. It’s low contrast, generous spacing and robust shapes make it work well in busy backgrounds with high readability. The design of letterforms is based on research and thorough testing on various devices ranging from high-end headsets to low-resolution smartphone-based devices. It has optical weights for high and low-resolution duplexed to avoid text reflow, making it easy to deliver a seamless user experience across platforms/devices. The functionality of the text has been tested thoroughly to make the reading experience better even in longer texts.
### Context

The rapid evolution of technology has prompted the type industry to consistently produce typefaces that are optimized for various environments and devices. AR One Sans is a font family that is specifically designed to support augmented and virtual reality environments, helping a wide range of users overcome technical limitations by providing a better reading experience. The font is not limited to AR and VR applications, and can also be used in contexts such as automobile dashboards, signage, and mobile applications.

### Design Features

- The design of the letterforms in AR One Sans is based on research and testing on a range of devices, from high-end headsets to low-resolution smartphone screens. This ensures that the font is able to withstand resolution and response time limitations, providing a consistently legible and user-friendly experience.
- The typeface uses the "Marionette formula," a design concept introduced by William A. Dwiggins. This formula substitutes straight lines for curves in certain letterforms, creating the illusion of more graceful curvature than is possible with actual curves. To achieve this effect, the typeface's cuts utilize the excess glow around the text to produce a smooth curve, resulting in letters with a more traditional shape, rather than those composed entirely of straight lines.
- The design is tested to improve the reading experience even in longer paragraphs, beyond small UI text strings.
- The letterforms are highly legible and have distinct shapes to avoid confusion between commonly misrecognized letters.
- The spacing and width of letters are optimized for negative polarity (light text on dark background) and angular distortion.
- The shapes are compatible with anti-interference techniques, which are recommended by researchers for better readability in AR environments.
- Specific design features have been added to reduce the effect of halation, and pixel loss in the lower resolution which causes the stroke ends to appear rounded.

### Generational Scalability
The scalability of the AR One Sans font family across different resolutions makes it an ideal choice not just for current-generation headsets, but also for future headsets. The font is also developed with a complex script in mind and has the ability to accommodate a wider design vocabulary (coming soon).

<img width="1600" alt="Text 2" src="https://user-images.githubusercontent.com/26871553/233612541-96b06c9d-2d24-4559-93f7-c03e585b816e.png">

## Variable Axes

| Axis | Tag | Range | Default | Description |
| --- | --- | --- | --- | --- |
| Augmented Reality Retinal Resolution | ARRR | 10 to 60 | 10 | Optimises the letter shapes and design to aid legibility based on the retinal resolution (PPD, pixel per degree) of devices. |
| Weight | wght | 400 to 700 | 400 | Regular to Bold |

**Augmented Reality Retinal Resolution Axis [ARRR]**

Resolution-specific enhancements optimize text without changing the width of the letters, maintaining consistent spacing and kerning, and preserving layout and line breaks. This ensures a consistent design and layout across different resolutions, making designs accessible and easy to read, regardless of the headset's resolution.

Retinal Resolution (pixel density) = the number of pixels in a horizontal display line divided by the horizontal field of view provided by the lens. 

Some of the adjustments in `ARRR` include: 

1. Addition of flaring at stroke ends to reduce the rounding effect at the ends due to missing pixels (in low resolution). It optimizes the shape of letters minimizing the rounding effect that can occur with rectangular strokes, making them appear more like rounded rectangles.
2. Light traps to reduce excess glow at the intersection of strokes.
3. Large x-height for a lower resolution to increase the counters and apertures and balance the negative space inside the letters due to flaring.

**Scale interpretation:** The lower value of the axis corresponds to the PPD of low-resolution headsets, while the upper value corresponds to 60 PPD, which is considered retina resolution. Beyond this point, the effect of adjustments on legibility and readability becomes negligible. Therefore, by limiting the adjustments to this range, designers can optimise the legibility and readability of their text for a wide range of headsets while minimising the amount of adjustment work required.

**Recommended Use:** map the `ARRR` to the retinal resolution of headsets and render the typefaces according to that.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL
