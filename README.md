# Resume Builder

This is a Java Swing application that helps users create a professional resume. The application provides a user-friendly graphical interface to enter personal details, educational qualifications, work experience, projects, and other relevant information. Once the information is provided, the application generates a PDF version of the resume using the iText library.

## Features

*   **User-Friendly Interface:** A multi-page GUI to guide the user through the resume-building process.
*   **Personal Information:** Fields for name, email, phone number, address, and social media links.
*   **Educational Background:** Sections for college/university and school details.
*   **Projects Section:** Allows users to showcase their projects with titles, links, and descriptions.
*   **Work Experience:** Fields for job titles, company names, duration, and descriptions of responsibilities.
*   **Skills and Interests:** Sections to list technical skills, languages, and personal interests.
*   **PDF Generation:** Creates a well-formatted PDF resume using the iText library.
*   **View Resume:** Option to open and view the generated PDF resume.

## Technologies Used

*   **Java:** The core programming language for the application.
*   **Java Swing:** Used for creating the graphical user interface (GUI).
*   **iText (5.5.10 & 7.0.2):** A Java library for creating and manipulating PDF documents.
*   **Maven:** A build automation tool used for project management and dependency handling.

## How to Run

1.  **Prerequisites:**
    *   Java Development Kit (JDK) 11 or higher installed.
    *   Apache Maven installed.

2.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/resume-builder.git
    cd resume-builder
    ```

3.  **Compile and run the application:**
    ```bash
    mvn clean install
    mvn exec:java -Dexec.mainClass="Resume.ResumeBuilder"
    ```

## How to Use

1.  **Personal Details:** Fill in your personal information on the first page and click "Next."
2.  **Education Details:** Provide your educational qualifications on the second page and click "Next."
3.  **Project Details:** Enter details about your projects on the third page and click "Next."
4.  **Experience Details:** Add your work experience on the fourth page and click "Next."
5.  **Extra Details:** Fill in your skills and interests on the fifth page and click "Submit."
6.  **Download Resume:** The application will generate the PDF resume and save it to your `E:` drive. You can then click the "VIEW" button to open the generated PDF.

## Project Structure

*   `src/Resume/ResumeBuilder.java`: The main class that creates the Swing GUI and handles user input.
*   `src/ResumeTemplate/ResumeTemplate.java`: This class takes the user's information and uses the iText library to generate the PDF resume.
*   `pom.xml`: The Project Object Model (POM) file for Maven, which defines the project's dependencies and build configuration.
*   `Fonts/`: Contains the fonts used in the PDF generation.
*   `Resume Builder Assets/`: Contains images and icons used in the GUI.

## Dependencies

The following dependencies are used in this project and are listed in the `pom.xml` file:

*   `com.itextpdf:kernel:7.0.2`
*   `com.itextpdf:io:7.0.2`
*   `com.itextpdf:layout:7.0.2`
*   `com.itextpdf:forms:7.0.2`
*   `com.itextpdf:pdfa:7.0.2`
*   `com.itextpdf:sign:7.0.2`
*   `com.itextpdf:barcodes:7.0.2`
*   `com.itextpdf:font-asian:7.0.2`
*   `com.itextpdf:itextpdf:5.5.10`
*   `com.itextpdf:hyph:7.0.2`

## Screenshots

*Screenshots of the application's interface could be added here to provide a better visual understanding of the application.*

## Contributing

Contributions are welcome! If you have any suggestions or find any bugs, please open an issue or submit a pull request.