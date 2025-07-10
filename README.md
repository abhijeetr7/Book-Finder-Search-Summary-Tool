# Book-Finder-Search-Summary-Tool

📚 Book Finder + Search Summary Tool
💡 Concept
The Book Finder + Search Summary Tool is a web application designed to help users discover books by searching for authors, titles, or genres. For each search result, it provides a summary, displays the book cover, shows its rating, and offers a preview link. Additionally, users can maintain a "Read Later" list directly within their browser.

✨ Features
Comprehensive Search: Search for books using various criteria:

Title: Find books by their exact title or keywords within the title.

Author: Discover books written by a specific author.

Genre: Explore books categorized under different genres (e.g., "Fiction", "Science Fiction", "History").

Detailed Book Information: Upon searching, each book card displays:

Book Cover Image

Title

Author(s)

Average Rating

Interactive Book Details Modal: Clicking on a book card (excluding the action buttons) opens a modal providing more in-depth information:

Extended Description/Summary

Publication Date

Page Count

Categories/Genres

Links to "Read Preview" (if available) and "More Info" on Google Books.

"Read Later" List:

Add books to a personal "Read Later" list for future reference.

Remove books from the "Read Later" list.

The list persists across browser sessions using Local Storage.

User-Friendly Interface:

Clear search input with a "Clear" button.

Loading indicator during searches.

Messages for no search results or an empty "Read Later" list.

Custom, non-intrusive alert messages for user actions (e.g., "Book added!").

"Scroll to Top" button for easy navigation on long pages.

Responsive Design: Optimized for seamless viewing and interaction across various devices (desktops, tablets, mobile phones).

🔧 Technologies Used
HTML5: For the core structure of the web page.

CSS3 (Tailwind CSS): For modern, utility-first styling and responsive design.

JavaScript (ES6+): For interactive functionality, API calls, and DOM manipulation.

Google Books API: Used for fetching book data, including titles, authors, descriptions, cover images, and preview links.

Web Storage API (Local Storage): For persisting the "Read Later" list in the user's browser.

▶️ How to Run
Save the file: Save the provided HTML code (from the book-finder-app Canvas) as an .html file (e.g., index.html).

Open in browser: Open the index.html file in any modern web browser.

No special server setup or dependencies are required as all necessary libraries (Tailwind CSS) are loaded via CDN.

🚀 Usage
Search for Books:

Enter your search query (e.g., "The Lord of the Rings", "J.K. Rowling", "Fantasy") into the search input field.

Select the appropriate search type ("Title", "Author", or "Genre") from the dropdown.

Click the "Search Books" button or press Enter.

View Search Results:

Book cards will appear in the "Search Results" section.

Click the "Read Later" button on any card to add it to your personal list.

Explore Book Details:

Click anywhere on a book card (except the "Read Later" button) to open a modal with more detailed information about the book.

Within the modal, you can click "Read Preview" to view a preview (if available) or "More Info" to go to the Google Books page.

You can also add/remove the book from your "Read Later" list directly from the modal.

Manage "Read Later" List:

The "My Read Later List" section displays all the books you've saved.

Click the "Remove" button on any card in this section to remove it from your list.

Clear Search:

Click the "×" button next to the search input to clear your current search query and results.

Scroll to Top:

If you scroll down the page, a "↑" button will appear in the bottom right corner. Click it to quickly return to the top of the page.

Enjoy discovering your next favorite book!
