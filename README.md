# youtube-thumbnail-downloader-
youtube-thumbnail-downloader

This YouTube Thumbnail Downloader includes all the key features you requested:

URL Input and Video ID Extraction:

Input field for YouTube URL with validation
Robust regex pattern to extract video ID from various YouTube URL formats
Error handling for invalid URLs
Thumbnail Generation:

Generates thumbnails in three sizes (default, HQ, maxres)
Displays thumbnails in a responsive grid
Fallback image when thumbnail isn't available
Download and Copy Options:

Download buttons for each thumbnail size
Copy URL functionality for each thumbnail
Proper file naming when downloading
UI/UX Features:

Clean, responsive design with Tailwind CSS
Loading states and error messages
Card-based layout with Shadcn UI components
Lucide React icons for better visual cues
The component is self-contained and doesn't require any external API calls. It handles all the thumbnail generation client-side by constructing the proper YouTube thumbnail URLs once the video ID is extracted.

The design is mobile-friendly and will work well on all screen sizes. The thumbnail grid adjusts from 1 column on mobile to 3 columns on larger screens.

To use this component, simply copy the code into a React project with the required dependencies (React, Tailwind CSS, Shadcn UI, and Lucide React icons). The component can be used as a standalone page or integrated into a larger application.
