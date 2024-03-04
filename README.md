# Recipe Sharing Application

This is a Recipe Sharing Application built using Angular. Users can post, view, edit, and delete recipes. The application features a user-friendly interface and implements Angular fundamentals such as components, services, routing, and forms.

## Core Features

1. **Recipe Display**
   - Home page displaying a list of recipes with titles, short descriptions, and thumbnail images.
   - Recipe detail view showing full recipe details including ingredients and cooking instructions.

2. **Adding Recipes**
   - Form for submitting new recipes with fields for title, description, ingredients, instructions, and an option to upload a thumbnail image.
   - Utilizes Angular Reactive Forms for form handling and validation.

3. **Editing and Deleting Recipes**
   - Functionality for users to edit or delete their posted recipes.

4. **Search Functionality**
   - Search bar allowing users to filter recipes by title or ingredients.

5. **Routing**
   - Angular Router implemented for navigation between home page, recipe detail view, and recipe submission form.
   - Includes a 404 Not Found page for unmatched routes.

## Technical Details

1. **Components**
   - Separate components for displaying the recipe list, recipe details, and recipe form.
   - Input and output decorators utilized for managing data flow between components.

2. **Services**
   - Recipe service handles operations like fetching, adding, editing, and deleting recipes.
   - Acts as a central point of interaction with a mock backend.

3. **Mock Backend**
   - json-server used to simulate a backend data store.

4. **Navigation and Routing**
   - Angular Router manages navigation.

5. **Validation and Error Handling**
   - Form validation ensures all fields are correctly filled out before submission.
   - Appropriate error messages displayed to the user.

## Bonus Feature (Optional)

**Favorites**
   - Users can mark recipes as favorites and filter by their favorite recipes.

## Evaluation Criteria

- **Functionality:** Core features implemented and working as described.
- **Code Quality:** Clean, well-commented code following Angular best practices.
- **UI/UX Design:** User-friendly interface with aesthetic appeal.
- **Technical Implementation:** Effective use of Angular concepts with bonus points for implementing optional feature.

## Deliverables

- Source code uploaded to a GitHub repository.
- Clear instructions in the README for setting up and running the application.
- Brief documentation explaining the application structure, key Angular features used, and any challenges encountered or additional features implemented.

## Setup and Running the Application

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Start the mock backend using `json-server --watch db.json`.
5. Start the Angular application using `ng serve`.
6. Access the application in your web browser at `http://localhost:4200`.

## Documentation

- **Application Structure:** The application follows a modular structure with separate components for different functionalities.
- **Key Angular Features Used:** Utilizes Angular concepts such as components, services, routing, forms, and input/output decorators.
- **Challenges Encountered:** Document any challenges faced during development and how they were addressed.
- **Additional Features Implemented:** List any additional features beyond the core requirements.

## Contributors

- [Your Name]
- [Other contributors, if any]

## License

This project is licensed under the [License Name] License. [Include license file if applicable]

---

Feel free to customize this README template according to your project's specific details and requirements.
