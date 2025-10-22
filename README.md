# Company Share Data Viewer American International Group (AIG)

This single-page responsive web application, built with Tailwind CSS and vanilla JavaScript, displays the maximum and minimum shares outstanding for a given company, primarily focusing on American International Group (AIG) by default.

## Features

*   **Default View**: Shows processed share data (max and min outstanding shares and their fiscal years) for American International Group (CIK: 0000005272).
*   **Dynamic CIK Loading**: Users can view data for any other publicly traded company by appending a CIK (Central Index Key) to the URL. For example: `index.html?CIK=0001018724` (for Apple Inc.).
*   **Responsive Design**: The layout adapts to different screen sizes, from mobile to desktop.
*   **Live Data Fetching**: When a CIK is provided in the URL, the application fetches the latest 