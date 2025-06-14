Assignment: Seamless Integration of a Person into a Scene

Tools Used:
- Google Colab
- Python (PIL / OpenCV)
- Google Drive

Steps Taken:
1. Took a front-facing photo of a person and removed its background.
2. Selected a suitable background image with soft indoor lighting.
3. Loaded both images using Python and resized the background to match.
4. Directly combined the person image onto the background using alpha compositing.
5. Skipped color transfer and shadow generation because the original image blended naturally.
6. Final result saved as final_composite.png

Missing Steps Identified:
- Shadow generation was unnecessary due to soft ambient light in the background.
- Color harmonization was attempted, but the original photo matched better visually.

Outcome:
The person has been seamlessly integrated into the background scene with realistic tone and lighting.
![Final Composite]: https://raw.githubusercontent.com/pratiksha270/Image-blending/main/final_composite.png
