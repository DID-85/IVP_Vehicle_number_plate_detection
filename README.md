# IVP_Vehicle_number_plate_detection
, the characters from the number plate should be recognized and displayed. The recognized characters should be correct, and the goal is to keep the process as simple as possible.


Number plate detection method scans the input image to identify and locate the license plate in
the image. Since a plate can exist anywhere in an image with various sizes, it is not possible to
check every pixel of the image to locate it[1]. The number plate of the vehicle is automatically
recognized and identified by comparing it with a database. It is difficult to detect the boundary
of the Number plate from the image of the car in an outdoor scene due to the color of characters
and background on the license plate. The process of locating the number plate consists of steps
like Edge Detection, Morphological operations, noise filtration, character segmentation, and
template matching.
