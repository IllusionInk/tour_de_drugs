# Tour De Drugs

>   The Tour de France is an annual men's multiple stage bicycle race primarily held in France. **The race is 3500kms long and last over 23 days.** 
Due to this intense nature of the sport, doping has been long associated with the race.The possibility of competition, rise in economic stakes produced a system of high rewards for winners.


*[Behance link](https://www.behance.net/gallery/72687679/Tour-De-Drugs-Data-Narrative) for detailed Design Documentation and interactive prototype of the narrative visualisation*

### Need ?
---
  - Doping stories are fixated primarily on breaking down the journey for accused.
  - The damage done to the sport and other riders is often unknown.  The larger story provides users a larger context of the practice of doping on the entire sport. 

#### Trigger Questions:
  - How wide was the impact of doping in the sport ?
  - How were the race results impacted ?
  - What role did the team doctors play ?
  - How bad was it for the riders who did not consume drugs ?
  - How many riders doped in the recent times ?

### Initial Data Analysis
---
- Required data was gathered from the wikipedia pages and other relevant cycling blog sites.
    - Doped data ( link), 
    - Team name (link ), 
    - Drug-doctor association (link)
    
#### Variable List
- **Drugged Riders+Team**
  - Year of race
  - Team
  - Rider_name
  - Rider_Status || Rider_mark (clean v/s doped)
  - Rank
  - Race Timing
  - Doctor associated with (if any)
- **Clean Rides**
  - Year of race 
  - Rider Name
  - Actual Finish Position
  - Clean Finish Position
- **Drug Network**
  - Year of Race
  - Doctor_name
  - Team || Current team name
  - Player Names
  - Rank
 
  ![table](https://github.com/IllusionInk/tour_de_drugs/blob/master/reference_assets/Data%20Gathering.jpg)

- Tableau + [Flourish App](https://public.flourish.studio/visualisation/98964/) explorations
![explorations](https://github.com/IllusionInk/tour_de_drugs/blob/master/reference_assets/Sketches.jpg)

### Story Structure
---
**Martini Glass Structure**
 - The narrative is author driven first introducing it,then moves to be a reder led initiative
 - The visualisation is built on Ben Shneiderman's principle of *Overview first, Details Later*; wherein I introduce the reader first to the concept of Tour De France and the history of doping in the sport. 
 - It then leads the reader to an exploratory dashboard,allowing him to comprehend the impact of doping on the sport; and further such analysis 

![structure](https://github.com/IllusionInk/tour_de_drugs/blob/master/reference_assets/Narrative%20Structure.jpg)

### Storyboarding
---
![sketch1](https://github.com/IllusionInk/tour_de_drugs/blob/master/reference_assets/Pencil%20Sketches.jpg)
![sketch2](https://github.com/IllusionInk/tour_de_drugs/blob/master/reference_assets/Storyboarding.jpg)


#### Visualisations
---
- **a) History of Doping - [View Prototype](https://vimeo.com/301324294)**
    ![doping_history](https://github.com/IllusionInk/tour_de_drugs/blob/master/viz_key/Doped%20Riders_bd1.jpg)
- **b) Impact on Clean Riders - [View Prototype](https://vimeo.com/301332973)**
    ![clean_history](https://github.com/IllusionInk/tour_de_drugs/blob/master/viz_key/Clean%20Riders_bd1.jpg)
- **c) Drug Network ( Doctor-Rider associations) - [View Prototype](https://vimeo.com/301334467)**
    ![drug_network](https://github.com/IllusionInk/tour_de_drugs/blob/master/viz_key/Drug%20Network%20bd1.jpg)

*Visit the [Behance link](https://www.behance.net/gallery/72687679/Tour-De-Drugs-Data-Narrative) for detailed Design Documentation of the narrative visualisation*
