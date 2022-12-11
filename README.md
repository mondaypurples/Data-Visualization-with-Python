Story:
Here we are looking into an automobile dataset which has various attributes like drive-wheels,body-style and price.

Lets view the snapshot of our selected dataset.

![dataframe](https://user-images.githubusercontent.com/93154330/206882025-ff92397c-4f74-43c5-819f-3cb5c1a6c3cd.png)




Here let's say we are selecting 3 important features drive-wheels, body-style and Price.

- The possible values of drive-wheels are 4 wheel Drive(4wd),Front WheelDrive(fwd) and Rear wheel Drive(rwd).

- The different body styles of the cars are hardtop,sedan,convertible and so on.

There are 2 types of people here:

        - A customer who wants to purchase the cars with less price , different body styles and wants to look for the drive wheel with this arrangement.

        - A dealer who wants to showcase the prices for the cars with different body styles and drive wheels.

As a data analyst, you have been given a task to visually show the body-style and prices with respect to each drive wheel selected.

So ideally you want to showcase this in the form of 2 interactive charts such as pie chart and bar chart on selection of drive wheel.

Below is the key item,

- Drive wheels 
- Components of the item
- Drive Wheel Type

For the chosen Drive wheel,

- Pie Chart showing body style and price.

- Bar Chart showing body style and price.

Expected Layout

![new_Layout](https://user-images.githubusercontent.com/93154330/206882036-39295fa4-9891-4b4a-8be4-69d21bbb4169.png)



Requirements to create the expected result
- A dropdown menu: For choosing Drive wheel type
- The layout will be designed as follows:
- An outer division with two inner divisions (as shown in the expected layout)
- One of the inner divisions will have information about the dropdown(which is the input) and the other one is for adding graphs(the 2 output graphs).
- Callback function to compute data, create graph and return to the layout.

To do:
1. Import required libraries and read the dataset
2. Create an application layout
3. Add title to the dashboard using HTML H1 component
4. Add a dropdown using dcc.dropdown
5. Add the pie chart and bar chart core graph components.
6. Run the app

Project Environment: Utilized Theia (Python runtime to create and launch Dash applications), an open-source IDE platform, that can be run on the cloud. 
