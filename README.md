# Image &amp; Video-Processing
Image &amp; Video Processing using OpenCV

## MOTION DETECTOR USING WEBCAM

- Using OpenCV Module, captured Video from webcam is three frames(GreyFrame, DeltaFrame, Threshold Frame)
- GrayFrame is to the captured base GrayScale image so as to compare it with other images for motion
- Delta Frame is to get the difference between GrayFrame and the Motion Captured Frames.
- Threshold Frame is to create white frames of the new images in the Frame.
- Used datetime module to capture the time when there are new images in the frame.
- Used Pandas to create dataframe as converted it to CSV file.
- Using Bookeh, plotted the motion graph, used HoverTool & ColumnDataSource and created a html graph.

