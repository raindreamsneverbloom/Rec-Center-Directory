<!-- In your HTML head -->
<link href="https://fonts.googleapis.com/css2?family=EB+Garamond&display=swap" rel="stylesheet">

<script lang='ts'>
  let searchTerm='';

  const idMap: Record<string, string> =  {
  'Abductors/Adductors': 'Abductors-Adductors',
  'Air Rower': 'Air-Rower',
  'Barbells': 'Barbells',
  'Belt Squat':'Belt_Squat',
  'Bench Press': 'Bench-Press',
  'Bicep Curl Machine': 'Bicep-Curl-Machine',
  'Cables': 'Cables',
  'Calf Raises':'Calf Raises',
  'Chest Fly Machine': 'Chest-Fly-Machine',
  'Chest Press': 'Chest-Press',
  'Deadlift':'Deadlift',
  'Dips': 'Dips',
  'Dumbbells': 'Dumbbells',
  'Elliptical':'Elliptical',
  'Glute Machine': 'Glute-Machine',
  'Hack Squat': 'Hack-Squat',
  'Hip Thrust':'Hip-Thrust',
  'Kettlebells': 'Kettlebells',
  'Lat Pulldown': 'Lat-Pulldown',
  'Leg Curl': 'Leg-Curl',
  'Leg Extension': 'Leg-Extension',
  'Leg Press':'Leg-Press',
  'Pullups': 'Pullups',
  'Punching Bags': 'Punching-Bags',
  'Rear Kick':'Rear-Kick',
  'Row': 'Row',
  'Shoulder Press': 'Shoulder-Press',
  'Smith Machine': 'Smith-Machine',
  'Squat Rack':'Squat-Rack',
  'Stairmaster': 'Stair-Master',
  'Stationary Bikes': 'Stationary-Bikes',
  'Treadmills': 'Treadmills'
};
  function handleScroll(){
    const id = idMap[searchTerm];
    if (id) {
      const targetSelection = document.getElementById(id);
      if (targetSelection) {
      targetSelection.scrollIntoView({ behavior: 'smooth' });
    }
  }
  }
</script>



<div class="equipment-page">

<a 
href="/" 
id="back-home" 
class="bg-gray-200 text-black px-4 py-2 rounded hover:bg-gray-300 transition inline-block mb-0">
← Back to Homepage
</a>

<div class ="max-w-2xl mx-auto p-4">
  <input
    type='text' 
    id='Searchbar'
    bind:value={searchTerm}
    on:change={handleScroll}
    placeholder="Search for Equipment"
    class="w-full p-2 mb-6 border rounded"
    list="search-suggestions"
  />
  <datalist id="search-suggestions">
    <option value="Abductors/Adductors"></option>
    <option value="Air Rower"></option>
    <option value="Barbells"></option>
    <option value="Belt Squat"></option>
    <option value="Bench Press"></option>
    <option value="Bicep Curl Machine"></option>
    <option value="Cables"></option>
    <option value="Calf Raises"></option>
    <option value="Chest Fly Machine"></option>
    <option value="Chest Press"></option>
    <option value="Deadlift"></option>
    <option value="Dips"></option>
    <option value="Dumbbells"></option>
    <option value="Elliptical"></option>
    <option value="Glute Machine"></option>
    <option value="Hack Squat"></option>
    <option value="Hip Thrust"></option>
    <option value="Kettlebells"></option>
    <option value="Lat Pulldown"></option>
    <option value="Leg Curl"></option>
    <option value="Leg Extension"></option>
    <option value="Leg Press"></option>
    <option value="Pullups"></option>
    <option value="Punching Bags"></option>
    <option value="Rear Kick"></option>
    <option value="Row"></option>
    <option value="Shoulder Press"></option>
    <option value="Smith Machine"></option>
    <option value="Squat Rack"></option>
    <option value="Stairmaster"></option>
    <option value="Stationary Bikes"></option>
    <option value="Treadmills"></option>
  </datalist>
</div>





<section id="Abductors-Adductors" class="equipment-card">
  <h1> Abductors/Adductors</h1>
  <ul class="bullets">
    <li>Floor 3 has 1 hip Abductor and 1 hip Adductor Machine</li>
    <li>Floor 6 has 1 hip Abductor and 1 hip Adductor Machine</li>
    <li>Floor 7 has 1 Plate Loaded Standing Abductor</li>
  </ul>
</section>

<section id="Air-Rower" class="equipment-card">
  <h1>Air-Rower</h1>
  <ul class="bullets">
    <li>Floor 3 has 4 Air Rower Machines</li>
    <li>Floor 6 has 2 Air Rower Machines</li>
    <li>Floor 7 has 3 Air Rower Machines</li>
  </ul>
</section>

<section id="Barbells" class="equipment-card">
  <h1> Barbells</h1>
  <ul class="bullets">
    <li>Floor 2 has many barbell racks and small barbells ranging from 50 to 100lbs</li>
    <li>Floor 4 has ~2 barbell racks and multiple Barbell bench/shoulder presses</li>
    <li>Floor 6 has 2 barbell racks</li>
    <li>Floor 7 has 3 barbell Racks that can be converted into Smith Machines</li>
  </ul>
</section>

<section id="Belt_Squat" class="equipment-card">
  <h1> Belt Squat</h1>
  <ul class="bullets">
    <li>Floor 7 has 1 Belt Squat</li>
  </ul>
</section>

<section id="Bench-Press" class="equipment-card">
  <h1> Bench Press</h1>
  <ul class="bullets">
    <li>Floor 2 has 2 Decline, 2 Flat, and 2 Incline Bench Presses</li>
    <li>Floor 4 has 2 Decline, 2 Flat, and 2 Incline Bench Presses</li>
  </ul>
</section>

<section id="Calf-Raises" class="equipment-card">
  <h1> Calf Raises</h1>
  <ul class="bullets">
    <li>Floor 2 has 1 Steaded Calf Raise</li>
    <li>Floor 3 has 1 Calf Extension Machine</li>
    <li>Floor 4 has 2 Steaded and 1 Plate Loaded Calf Raise Machine</li>
  </ul>
</section>

<section id="Bicep-Curl-Machine" class="equipment-card">
  <h1> Bicep Curl Machine</h1>
  <ul class="bullets">
    <li>Floor 3 has 1 Bicep Curl Machine</li>
    <li>Floor 6 has 1 Bicep Curl Machine</li>
    <li>Floor 7 has 1 Plate Loaded Bicep Curl</li>
  </ul>
</section>

<section id="Cables" class="equipment-card">
  <h1> Cables</h1>
  <ul class="bullets">
    <li>This section is just individual cables that are multi-purpose</li>
    <li>Floor 2 has 10 Cables (All connected in 2's)</li>
    <li>Floor 3 has 6 Cables (1 Pair Connected in 2's)</li>
    <li>Floor 4 has 6 Cables</li>
    <li>Floor 6 has 2 Cables (1 Pair Connected in 2's)</li>
    <li>Floor 7 has 8 Cables (2 Pairs Connected in 2's)</li>
  </ul>
</section>

<section id="Chest-Fly-Machine" class="equipment-card">
  <h1> Chest Fly Machine</h1>
  <ul class="bullets">
    <li>Floor 3 has 1 Chest Fly Machine</li>
  </ul>
</section>

<section id="Chest-Press" class="equipment-card">
  <h1> Chest Press Machine</h1>
  <ul class="bullets">
    <li>Floor 2 has 2 Plate Loaded Chest Press</li>
    <li>Floor 3 has 1 Chest Press Machine</li>
    <li>Floor 4 has 2 Plate Loaded Chest Press</li>
    <li>Floor 6 has 1 Chest Press Machine</li>
  </ul>
</section>

<section id="Deadlift" class="equipment-card">
  <h1> Deadlift</h1>
  <ul class="bullets">
    <li>Floor 3 has 4 Bodyweight, 1 assisted, and 1 machine Dip station</li>
    <li>Floor 7 has 1 Plate Loaded Deadlift</li>
  </ul>
</section>


<section id="Dips" class="equipment-card">
  <h1> Dips</h1>
  <ul class="bullets">
    <li>Floor 3 has 4 Bodyweight, 1 assisted, and 1 machine Dip station</li>
    <li>Floor 6 has 1 Dip Machine</li>
    <li>Floor 7 has 1 Plate Loaded Seated Dip</li>
  </ul>
</section>

<section id="Dumbbells" class="equipment-card">
  <h1> Dumbbells</h1>
  <ul class="bullets">
    <li>Floor 2 has Heavier Dumbbells with ~5 benches ranging from 50 to 100lbs</li>
    <li>Floor 3 has Lighter Dumbbells ranging from 2.5 to 30lbs (no benches available)</li>
    <li>Floor 4 has Lighter Dumbbells with many benches ranging from 0 to 50lbs</li>
    <li>Floor 6 has Lighter Dumbbells with ~8 benches ranging from 5 to 50lbs</li>
    <li>Floor 7 has Lighter Dumbbells with ~4 benches ranging from 5 to 50lbs</li>
  </ul>
</section>

<section id="Elliptical" class="equipment-card">
  <h1> Elliptical</h1>
  <ul class="bullets">
    <li>Floor 3 has 2 Ellipticals</li>
    <li>Floor 7 has 3 Ellipticals</li>
  </ul>
</section>

<section id="Glute-Machine" class="equipment-card">
  <h1> Glute Machine</h1>
  <ul class="bullets">
    <li>Floor 3 has 1 Glute Machine</li>
    <li>Floor 6 has 1 Glute Machine</li>
  </ul>
</section>

<section id="Hack-Squat" class="equipment-card">
  <h1> Hack Squat</h1>
  <ul class="bullets">
    <li>Floor 2 has 1 Hack Squat</li>
    <li>Floor 7 has 1 Hack Squat</li>
  </ul>
</section>

<section id="Hip-Thrust" class="equipment-card">
  <h1> Hip Thrust</h1>
  <ul class="bullets">
    <li>Floor 4 has 2 Plate Loaded Hip Thrust</li>
    <li>Floor 7 has 1 Plate Loaded Hip Thrust</li>
  </ul>
</section>

<section id="Kettlebells" class="equipment-card">
  <h1>Kettlebells</h1>
  <ul class="bullets">
    <li>Floor 3 has Kettlebells</li>
    <li>Floor 7 (Courts Overlook Room) has Kettlebells 4 - 24lbs</li>
  </ul>
</section>

<section id="Lat-Pulldown" class="equipment-card">
  <h1>Lat Pulldown</h1>
  <ul class="bullets">
    <li>Floor 2 has 1 Plate Loaded and 2 Cable Lat Pulldowns</li>
    <li>Floor 3 has 2 Cable Lat Pulldowns</li>
    <li>Floor 4 has ~1 Plate Loaded Lat Pulldown</li>
    <li>Floor 6 has 1 Lat Pulldown Machine</li>
    <li>Floor 7 has 1 Plate Loaded Lat Pulldown</li>
  </ul>
</section>

<section id="Leg-Curl" class="equipment-card">
  <h1>Leg Curl</h1>
  <ul class="bullets">
    <li>Floor 3 has 1 Seated and 1 Lying Leg Curl Machine</li>
    <li>Floor 6 has 1 Seated Leg Curl Machine</li>
    <li>Floor 7 has 1 Plate Loaded Standing Leg Curl</li>
  </ul>
</section>

<section id="Leg-Extension" class="equipment-card">
  <h1>Leg Extension</h1>
  <ul class="bullets">
    <li>Floor 3 has 1 Leg Extension Machine</li>
    <li>Floor 6 has 1 Leg Extension Machine</li>
    <li>Floor 7 has 1 Plate Loaded Leg Extension Machine</li>
  </ul>
</section>

<section id="Leg-Press" class="equipment-card">
  <h1>Leg Press</h1>
  <ul class="bullets">
    <li>Floor 2 has 2 Plate Loaded Leg Press</li>
    <li>Floor 3 has 1 Leg Press Machine</li>
    <li>Floor 6 has 1 Leg Press Machine</li>
    <li>Floor 7 has 2 Plate Loaded Leg Press</li>
  </ul>
</section>

<section id="Pullups" class="equipment-card">
  <h1>Pullups</h1>
  <ul class="bullets">
    <li>Floor 3 has 1 assisted and 2 obnoxious bodyweight pullup spots</li>
  </ul>
</section>

<section id="Punching-Bags" class="equipment-card">
  <h1>Punching Bags</h1>
  <ul class="bullets">
    <li>Floor 3 has 6 Punching Bags</li>
  </ul>
</section>

<section id="Rear-Kick" class="equipment-card">
  <h1>Rear Kick</h1>
  <ul class="bullets">
    <li>Floor 7 has 1 Plate Loaded Rear Kick</li>
  </ul>
</section>

<section id="Row" class="equipment-card">
  <h1>Rows</h1>
  <ul class="bullets">
    <li>Floor 2 has 1 Plate Loaded Row</li>
    <li>Floor 3 has 2 Cable Rows</li>
    <li>Floor 6 has 1 Row Machine</li>
    <li>Floor 7 has 2 Plate Loaded Rows (1 Low Row) and 2 Cable Rows</li>
  </ul>
</section>

<section id="Shoulder-Press" class="equipment-card">
  <h1>Shoulder Press</h1>
  <ul class="bullets">
    <li>Floor 2 has 2 Plate Loaded Shoulder Press</li>
    <li>Floor 3 has 1 Shoulder Press Machine</li>
    <li>Floor 4 has 2 Barbell and 2 Plate Loaded Shoulder Press</li>
    <li>Floor 6 has 1 Shoulder Press Machine</li>
  </ul>
</section>

<section id="Smith-Machine" class="equipment-card">
  <h1>Smith Machine</h1>
  <ul class="bullets">
    <li>Floor 4 has 3 Smith Machines</li>
    <li>Floor 7 has 2 Smith Machines</li>
  </ul>
</section>

<section id="Squat-Rack" class="equipment-card">
  <h1> Squat Rack</h1>
  <ul class="bullets">
    <li>Floor 2 has ~12 Squat racks </li>
    <li>Floor 4 has ~2 Squat racks</li>
    <li>Floor 6 has 2 Squat racks</li>
    <li>Floor 7 has 3 Squat Racks that are also Smith Machines</li>
  </ul>
</section>

<section id="Stair-Master" class="equipment-card">
  <h1>Stair Masters</h1>
  <ul class="bullets">
    <li>Floor 3 has 4 Stair Masters</li>
    <li>Floor 4 has 5 Stair Masters</li>
    <li>Floor 6 has 4 Stair Masters</li>
    <li>Floor 7 has 6 Stair Masters</li>
    <li>Floor 7 (Courts Overlook Room) has 6 Stairmasters</li>
  </ul>
</section>

<section id="Stationary-Bikes" class="equipment-card">
  <h1>Stationary Bikes</h1>
  <ul class="bullets">
    <li>Floor 3 has 4 Stationary Bikes</li>
    <li>Floor 6 has 4 Stationary Bikes</li>
    <li>Floor 7 has 5 Stationary Bikes</li>
    <li>Floor 7 (Courts Overlook Room) has 6 Stationary Bikes</li>
  </ul>
</section>

<section id="Treadmills" class="equipment-card">
  <h1>Treadmills</h1>
  <ul class="bullets">
    <li>Floor 3 has 8 treadmills</li>
    <li>Floor 4 has 15 treadmills</li>
    <li>Floor 6 has 3 Treadmills</li>
    <li>Floor 7 has 17 regular and 2 curved Treadmills</li>
    <li>Floor 7 (Courts Overlook Room) has 5 Treadmills</li>
  </ul>
</section>











<a href="/" id="back-home" class="bg-gray-200 text-black px-4 py-2 rounded hover:bg-gray-300 transition">
  ← Back to Homepage
</a>



</div>



<style>

  .equipment-card{
    text-align: center;
    margin: .5rem 2rem; /* top/bottom , left/right */
    padding: 1rem; 
    border-radius: .25rem;
    background-color: rgb(10, 40, 70);
    text-align: left;
    font-family: 'EB Garamond', serif;
  }
  .bullets{
    list-style-type: disc;
    padding-left: 1.25rem;
  }
  h1 {
  margin: 0;
  /* Keep existing styles */
  font-size: 1.75rem;
  padding-left: 0.25rem;
  color: rgba(255, 205, 5, 0.877);
  font-weight: 150;
}
   #back-home {
    display: inline-block;       /* Ensures margin works */
    margin-top: 0.5rem;            /* Adds space above */
    margin-bottom: 0.1rem;       /* Adds space below */
    padding: 0.5rem 1rem;
    background-color: rgb(10, 40, 70);   /* Tailwind gray-200 */
    color: rgba(255, 205, 5, 0.877);
    border-radius: 0.375rem;
    text-decoration: none;
    transition: background-color 0.2s ease;
    margin-left: auto;
    margin-right: auto;
  }

  #back-home:hover {
    background-color: #d1d5db;   /* Tailwind gray-300 */
    color: rgb(0, 0, 0);
  }
  
  .equipment-page{
  background-color: rgb(0, 25, 51);
  min-height: 100vh;
  color: white;
  font-size:1.1rem;
}

  #Searchbar{
  border-color: gold;
  border-width: .1rem;
  color: white;
  background-color: rgb(10, 40, 70);
}
  
  
  </style>
