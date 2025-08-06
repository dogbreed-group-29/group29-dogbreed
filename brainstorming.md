
# Brainstorming Ideas

## Idea 1: WeatherNow (Weather Forecast App)

**Description**:  
An app where users can search any city and view the 5-day weather forecast using the OpenWeatherMap API. The app would display temperature, weather description, humidity, wind speed, and precipitation data in a user-friendly format.

**Challenges Faced**:  
- API integration proved difficult during development.
- Despite multiple debugging attempts, the API did not return expected responses even with a valid key.
- Switching to another weather API (e.g., MetaWeather) still required restructuring the data models and UI.
- Time constraints made it impractical to continue down this path.

**Decision**: Dropped due to API issues and inconsistent data parsing.

---

## Idea 2: DogBreed Gallery (Final Choice)

**Description**:  
An app where users can search for various dog breeds and view related images using the Dog CEO API. Features included search filtering, breed selection, and a visually pleasing gallery UI using RecyclerView.

**Reasons for Selection**:
- Fully functional and reliable API with simple endpoints.
- Easily accessible image data enabled faster development and UI testing.
- The app concept was fun, engaging, and allowed room for extra features like favorites, random breeds, or dog facts.
- Perfect fit for learning and applying API integration, RecyclerView, and UI/UX design skills.

**Decision**: Chosen as final app idea due to stability, ease of API use, and engaging user experience.

---

## Idea 3: Pokémon Viewer App

**Description**:  
An app to search and display Pokémon details using the PokeAPI. Users could view Pokémon names, images, types, and base stats.

**Challenges Considered**:  
- Although the API worked well, displaying large amounts of data (e.g., stats and evolutions) required complex parsing.
- The app structure risked becoming too data-heavy and overwhelming for a milestone-level project.
- Would require pagination, JSON handling, and design effort beyond the time constraints.

**Reason for Rejection**:  
Despite being fun and nostalgic, the Pokémon app idea was deprioritized due to scope complexity. The team decided that DogBreed Gallery struck the best balance between feasibility, polish, and creativity.

---

## Final Decision:
We chose **DogBreed Gallery** as our final app because:
- It provided the best API support out of the three.
- Development and testing were more manageable within the milestone timeframe.
- It allowed for expressive design and interactivity without overloading functionality.
