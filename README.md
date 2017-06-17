# Fitness-Tracker
A way to track workouts on your own terms.

This app will allow you to input your own exercises, eliminating the need to search through hundreds of options wihtout finding an exact match!

- Tracks lbs & inches lost (Weight)
- Tracks exercises done (Exercises)

Requirements for Exercises
1 Title of Sheets (references to where exercises come from)
2 Date of Exercise
2 Entry for Exercise Name, Perceived Exertion, Total Weight, Sets
        Unlimited rows (exercises) and unlimited columns (sets)
        Exercise Name is a CharField
        Total Weight is an IntegerField
        Sets Entry will be an integer that goes up to 20
3 Notes section beneath rows
4 Ability to save these sheets as templates


Requirements for Weight
1 Date of entry
2 Entry for weight - format = 0.0
3 Entry for tracked body measurements:
        Bust, Waist, High Hip, Hip, Left Thigh, Right Thigh, Left Calf, Right Calf, Left Bicep, Right Bicep
