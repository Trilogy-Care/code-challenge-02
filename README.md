# **Task Instructions**

## **Objective**
The goal of this task is to demonstrate your ability to work with Laravel by building functionality as described below. You are free to determine the best way to structure your code and files to achieve the stated goals.

---

## **Requirements**

1. **Create a Command to Assign Bills**:
   - Implement a Laravel command that assigns unassigned bills in the `submitted` stage to a user.
   - Ensure that no user is assigned more than 3 bills at any given time.

2. **Design VueJS Page**:
   - Design a VueJS page to show the following design.
   - Either using InertiaJS (preferred) or an alternative method, the frontend should receive data relevant to display the design.
   - This will require various controllers etc to query data in order to render the view. How you structure this is up to you, but use it to show your understanding of the Laravel framework building for scale.

   **Design Reference**:

   ![Page Design](https://trilogy-care-public-hosted.s3.ap-southeast-2.amazonaws.com/other/design.png)

3. **Create an Endpoint to Add Bills**:
   - Implement an API endpoint to add a new bill to the database.
   - Ensure the `bill_reference` field is unique to prevent duplicate entries.

4. **Testing**:
   - Write tests for all backend functionality you create to ensure robustness and correctness.


## **Setup**
We have setup this project to use Vue3, TailwindsCSS and InertiaJS, which is our current tech stack. The purpose of this is to save you time configuring the project. If you are familiar with this stack, then please utilise it, using ```php artisan serve``` and ```npm run dev```. This site will be accessible at localhost:8000.


Run the migration and seeder to populate the database with dummy data: 

```
php artisan migrate --seed
```

In order to copmlete this task, you will need to create or modify relevant files in this project. You can determine the best approach to structure your code, JSON and any other files in order to achieve the stated goals and demonstrate your understanding of the Laravel framework.

## **Additional Notes**

This task should take 3 hours to complete.

For the front end requirements, the focus should be on structure rather than visuals. You can use the InertiaJs setup or  feel free to use something you are more familiar with if you want to do show your front end skills.

## **How to submit**

Send a zip of the files and email: anthonyr@trilogycare.com.au


