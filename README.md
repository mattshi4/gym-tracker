# gym-tracker
Gym progress tracker built on t3

Minimum requirements:
Add a new exercise type: squat, bench etc
For each exercise type, a progression history: 3 sets 10 reps at x kg
A workout (a collection of exercises on a given date), automatically add
exercise information from a workout to an exercise's history. 
Be able to filter for date and search through these workouts.
Be able to filter workouts by a tag: back etc.

Goal requirements:
AI assistant that you can ask questions, it will access database and then
give user personalised advice.
Some sort of interface where user can track weight/strength goals

Start workout flow:
Add workoutType if needed (split archetypes basically, legs, arms etc.)
Add new exercise if required (incline bench, lat pulldowns etc.)
Add a workout, add the workoutType to the workout. 
Add exercises from a drop-down list populated by entries in Exercise table. 
Add exerciseInstances once we complete an exercise.
Exercise instance will automatically be parsed through and added to an Exercise's
record
End workout, gets added to our workout history

