# bikesharing

## Challenge
Convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Challenge Deliverables
- Deliverable 1: Change Trip Duration to a Datetime Format using Pandas
- Deliverable 2: Create Visualizations for the Trip Analysis in Tableau
- Deliverable 3: Create a Story and Report for the Final Presentation published to Tableau Public

## Challenge Results
- Deliverable 1: 
  -  See NYC_Citibike_Challenbge.ipynb python pandas transformation of the tripduration to datetime using<br>
     _citibike_tripdata["tripduration"] = pd.to_datetime(citibike_tripdata["tripduration"], unit='s')_
 ![Snap209](https://user-images.githubusercontent.com/90797036/147394338-c4daf1cf-b96f-4347-b7ac-8fad2546200f.png)    
- Deliverable 2: 
  - See the Module 14 Challenge 'Trip Story/Deliverable 2' created using the slides built as described:
  https://public.tableau.com/app/profile/katey.harris/viz/Module14Challenge_16403066521090/CitiBikeDrillDownTotals
  ![Snap210](https://user-images.githubusercontent.com/90797036/147394357-51c9154d-d024-45ed-90f6-a849bdf9166a.png)

- Deliverable 3:
  - See the Citi Bike Drill down totals story which is a drill down of Totals overall, then totals by busiest day, then by busiest times and busisiet destination:
  https://public.tableau.com/app/profile/katey.harris/viz/Module14Challenge_16403066521090/CitiBikeDrillDownTotals
  ![Snap211](https://user-images.githubusercontent.com/90797036/147394412-cc2d2f0b-7957-4c13-8842-c76b04c5e150.png)

- Also see additional Search Story
  - Search by Start station or Destination  
  https://public.tableau.com/app/profile/katey.harris/viz/Module14Challenge_16403066521090/CitiBikeDrillDownTotals
![Snap1](https://user-images.githubusercontent.com/90797036/147394436-a8ab7d80-fd73-4ab3-a307-4137f5d90fc5.png)
