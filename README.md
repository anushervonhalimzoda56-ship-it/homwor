# homwor
In English: Instead of using a standard Layout Grid in Figma, it is much easier to apply Auto Layout with a Horizontal direction (row). For both the left and right column frames inside, set the horizontal resizing property to Fill Container. This ensures they split the available space evenly and responsively when resized.
3. Asymmetric Photo Collage (⁠grid grid-cols-4 auto-rows-[...]⁠)
 In English: Auto Layout won't work for this specific section. To replicate this "staggered/broken" collage effect, create a standard Frame (not Auto Layout). Arrange your photo layers into groups manually, then apply Constraints set to Left & Right and Top & Bottom so that the images scale proportionally when the parent frame shrinks or expands.
