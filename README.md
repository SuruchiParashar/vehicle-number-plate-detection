# vehicle-number-plate-detection
The objective is to design an efficient automatic authorized vehicle identification system by using the vehicle number plate. The system is implemented on the entrance for security control of a highly restricted area like military zones or area around top government offices e.g. Parliament, Supreme Court etc. The developed system first detects the vehicle and then captures the vehicle image. Vehicle number plate region is extracted using the image segmentation in an image. Optical character recognition technique is used for the character recognition. The resulting data is then used to compare with the records on a database so as to come up with the specific information like the vehicle’s owner, place of registration, address, etc. The system is implemented and simulated in MATLAB, and it performance is tested on real image. It is observed from the experiment that the developed system successfully detects and recognize the vehicle number plate on real images.

# BACKGROUND

The idea behind this implementation is to provide fundamental protection against any external disturbance. Vehicle Number Plate detection helps the security system to relate and match the data with the records and create a safe environment. Since, Vehicle number plate is the only unique code for vehicle identification in any country database; it is an important resource for accessing data of the owner and other relevant information from the country information Systems. This is simply the ability to automatically extract and recognition a vehicle number plate's characters from an image. 
So, the implementation of this project is completely focused on the safety systems. We have tried to look every possible way in which we can recognize the vehicle number plate and convert it into the detectable state by which it can be further extracted.
The techniques used are basic functions of Image Processing, which are implemented using MATLAB syntaxes.


# PROCESS:

License Plate Recognition is an image processing technology which uses number (license) plate to identify the vehicle.The objective is to design an efficient automatic authorized vehicle identification system by using the vehicle number plate.The developed system first detects the vehicle and then captures the vehicle image. Vehicle number plate region is extracted using the image segmentation in an image. Optical character recognition technique is used for the character recognition.The resulting data is then used to compare with the records on a database so as to come up with the specific information like the vehicle owner, place of registration, and address.

The software aspect of the system runs on standard home computer hardware and can be linked to other applications or databases. It first uses a series of image manipulation techniques to detect, normalize and recognise the image of the number plate, and then optical character recognition (OCR) to extract the alpha-numeric of the license plate. This Automatic Number Plate Recognition system canbe generally deployed in one of two basic approaches: one allows for the entire process to be performed at the lane location in real-time, and the other transmits all the images from many lanes to a remote computer location and performs the OCR process there at some later point in time. Here we have designed the system such that it gives the output in textual form after segmentation and recognition. 

Since the vehicle plates are based on different country standards, they usually different in form, shape and material. Therefore, the LPR systems are country specific and are adapted to the country where they are installed and used. Our system will recognize the image taken by the IR cameras and just give the output in the textual form regardless of the country specifics.

Some plates have additional information written or attached to the plate, such as state identification, province initials, plate issue date label, vehicle type, country flag and more. For most applications this additional information is not required (and is usually not identified due to the complexity, variation, quality and resolution). Thus, we only intend to give the registered number as the output.

<p align="center">
  <img src="https://github.com/SuruchiParashar/vehicle-number-plate-detection/blob/master/ezgif.com-video-to-gif%20(1).gif
" />
</p>


# HARDWARE REQUIREMENTS 

Here, the detection is completely based on MATLAB code; therefore no hardware implementation is used. The actual security systems which connect this project with the database use Hardware. We are directly providing images to the system, while the actual implementation requires certain cameras and servers.
A camera that take the images of the car (front or rear side). A controlled light that can bright up the plate, and allow day and night operation. In most cases the illumination is Infra-Red (IR) which is invisible to the driver. An interface board between the camera and the PC, allows the software to read the image information. A PC running Windows or Linux. It runs the LPR application which controls the system, reads the images, analyses and identifies the plate, and interfaces with other applications and systems.


# SOFTWARE REQUIREMENTS

The MATLAB application and the recognition package. Usually the recognition package is supplied as a DLL (Dynamic Link Library). A database software in which the events are recorded on a local database or transmitted over the network. The data includes the recognition results and (optionally) the vehicle.

