Source: NASA Arctic-Boreal Vulnerability Experiment (ABoVE)
Citation: Sivy ,K.J., A.W. Nolin, C.L. Cosgroce, and L.R. Prugh (2018). ABoVE: Dall Sheep Track Sinking Depths, Snow Depth, Hardness, and Density, 2017.
Size: 133 rows, 8 columns
Features:
    track_survery_ID: ID number of the specific track site survery (ranges from 10-45)
    layer_number: Sequential layer number in the snow pit, measured from surface to ground.
    depth_top_layer: Distance from the ground to the top of the snow layer in centimeters
    depth_bottom_layer: Distance from the ground to the bottom of the snow layer in centimeters
    layer_thickness: Thickness of the specific snow layer in centimeters
    hand_hardness: Standard hand-hardness code (F = fist, 4F = 4 Fingers, 1F = 1 Finger, P = pencil, K = knife)
    category: Snow resistance classification ("soft" for index 1-3, "hard" for index 4-5)
    Index: Numerical scale of snow hardess from 1 (softest) to 5 (hardest)
 Potential Issues: 
    Missing values in NASA ABoVE are represented by -9999 and must be filtered during data cleaning.
    Hand-hardness testing relies on manual field tests in snow pits, which introduces human erorr.
    The data was collected over a 4 day period (March 19-22, 2017) and at the same location (Jaeger Mesa in Wrangell-St.Elias National Park and Preserve, Alaska), meaning the data may not be an accurate representation of the relationship between snow layer and thickness and snow hardness.