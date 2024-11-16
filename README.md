# Simple Animal Search App

## Description

This is a simple Android application that allows users to search for animals using the [API Ninjas Animals API](https://api-ninjas.com/api/animals). The app displays the search results in a scrollable list and provides details about each animal. Users can filter animals using the search bar. The application uses modern Android development practices, ensuring a responsive and user-friendly experience.

---

## Features

1. **Search Functionality**: Allows users to search for animals by name.
2. **RecyclerView with DiffUtil**: Displays a list of animals efficiently with automatic updates for data changes.
3. **API Integration with Retrofit**: Fetches animal data from the API Ninjas Animals API.
4. **Detailed Animal Information**: Displays at least five fields for each animal, including name, taxonomy, habitat, diet, and lifespan.
5. **Responsive and Clean UI**: A user-friendly interface for seamless interaction.

---

## Technologies Used

- **RecyclerView**: For displaying lists efficiently.
- **Retrofit**: For making network requests to the Animals API.
- **DiffUtil**: For optimizing RecyclerView updates.
- **LiveData and ViewModel**: For managing UI state.
- **Gson**: For parsing JSON responses.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AlanC8/animal-api.git
   ```
2. Open the project in **Android Studio**.
3. Add your API key in the `ApiSource` class:
   ```kotlin
   .addHeader("X-Api-Key", "YOUR_API_KEY")
   ```
4. Build and run the application on an emulator or physical device.
5. Use the search bar to find animals by name.

---

## Video Demonstration

[Watch the video demonstration](https://drive.google.com/file/d/13ZjDbQ3tah0t1X0QVvGbYWnUFYOH7BUy/view?usp=sharing)

---
## Searching pic Demonstration

<img width="422" alt="Screenshot 2024-11-16 at 23 22 43" src="https://github.com/user-attachments/assets/7a435334-9bc3-42b1-8fcb-577388a5fac5">

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
