# Pure-Bengali-Font-In-Matplotlib

1. Matplotlib is a popular Python library used for creating data visualizations.
2. Bengali is a language spoken in the Indian subcontinent and requires a specific font to be displayed correctly.
3. There are multiple ways to represent Bengali text, including Unicode.
4. When using Unicode to represent Bengali text in Matplotlib, the text may appear broken due to the limitations of the default font.
5. To display Bengali text unbroken in Matplotlib, I have used ANSI Bengali Font here.
6. The Bangla ANSI font can be downloaded and installed on the system or imported into the Python script.
7. After importing the font, it can be used to display Bengali text in Matplotlib using the `fontproperties` parameter of the `text` function.
8. The `fontproperties` parameter should be set to the `FontProperties` object created using the imported Bangla font.
9. Additionally, the font size can also be adjusted using the `fontsize` parameter of the `text` function.
10. This approach allows users to create visually appealing and accurate data visualizations in Bengali language using Matplotlib, without the problem of broken text that occurs when using Unicode representation.
