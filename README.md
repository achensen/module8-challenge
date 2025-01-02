# Vehicle Builder
  ![license badge](https://img.shields.io/badge/license-MIT-blue)
## Table of Contents
* [Description](#description)
* [License](#license)
* [Installation](#installation)
* [Usage](#usage)
* [Contributions](#contributions)
* [Contact Information](#contact-information)
* [Walkthough Video](#walkthrough-video)
* [Additional Notes](#additional-notes)

## Description
This code allows the user to input data and make selections from the command line in 
order to find several vehicle conditions. 

## License
This project is licensed with MIT

## Installation 
npm inquirer

## Usage
* To get started run `npm start` in the command line

* You will then be promoted in the command line if you would like to create a new vehicle perform an action on an existing one 

    ![CLI Screenshot](/images/Screenshot%20%20Vehicle%20Builder%201.png)

* If you select the option to create a new vehicle you will be asked choose between the following options
    * Car
    * Motorbike
    * Truck

* Next you will be prompted to input the vehicle color, make, model, year, weight, top speed , and in the instance of choosing a truck the towing capacity  

    ![CLI screenshot of prompts with F-150 input](/images/Screenshot%20Vehicle%20Builder%202.png)

* You will then be able to choose from a variety of actions for your selected or input vehicle

    * If you would like to select a different vehicle you can return to the first promt. As you can see my F-150 was added now to the options for an existing vehicle 

    ![F150 added as user imput show as option in existing](/images/Screenshot%20Vehicle%20Builder%20F150%20added%20to%20list%20.png)


## Vehicle Actions
Each vehicle type handles actions differently, just like they would on the road
### Trucks
If you select a truck as your vehicle you have the option to perform the `Tow` action that is only available for this vehicle type
* Select `Tow` in the list of actions
* Next select which vehicle from the list you would like to tow

    ![Toyota Camry selected as vehicle to be towed](/images/Screenshot%20Vehicle%20Builder%20Towing%20feature.png)

* If the weight is less than the maximun towing capacity of the truck selected you will see in the command line that your selected vehicle is now being towed 
* Then you are free to perform another action with your truck 

### Motorbikes
Motorbikes have the special ability to perform a Wheelie, unlike a truck or car

* Select an existing Motorbike or input the specifications just like for truck

    ![Existing Selection Harvey Davisdson](/images/Screenshot%20Vehicle%20Builder%20Motorbike%20Selection.png)

* You can now select `Wheelie` from the list of actions and see that if was performed by your Motorbike

    ![Wheelie action selected and performed by Harley](/images/Screenshot%20Vehicle%20Builder%20Motorbike%20Wheelie.png)

### Car
For car we will look at the options that are available for all vehicles

* Select or input a car from the command line and move through the list of actions to see the resposes
    * `Start vehicle` will display `Vehicle started`
        * You must have the vehicle started to run turn right, turn left, and reverse
    * `Turn right` will display `Vehicle turned right`
    * `Turn left` will display `Vehicle turned left`
    * `Reverse` will display `Vehicle reversed`
    * `Accelerate 5 MPH` will display new speed in increments of 5 ascending `Vehicle accelerated to 5 mph`
    * `Decelerate 5 MPH` will display new speed in incements of 5 decending `Vehicle decelerated to 0 mph`
    * `Stop vehicle` will reset new speed to 0 and display `Vehicle stopped`
    * `Print details` will display all vehivle information saved in the console

        ![All vehicle information for the Car selected](/images/Screenshot%20vehicle%20Builder%20Car%20Print%20Details.png)


## Contributions
Myself, with some tutoring assistance (see additional notes)

## Contact Information
My GitHub account is [GitHub Account Link](https://github.com/achensen)
To email me you can contact me at erinrjacobsen@gmail.com

## Walkthrough Video
Please follow this link for my Screencastify walkthrough :

## Additional Notes 
The initial code for this project was provided by EDX Engineering Services Company to complete an assingment for a Full Stack Web Development Course. My contribution was to complete the code to ensure it had full functionality. I did recieve tutoring assistance to help with my understanding of this assignment, specifically with Trucks.ts and learning how to leverage specific vehicle information in order to dercerne weather something would be towed or not, I also recieved assistance for Typscript synax durinf this challenge.  