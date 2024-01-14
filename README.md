# Project Readme

## Overview

This project aims to enhance the user experience on the [Consors Bank Best Offers](https://aktionen.consorsbank.de/ev/ev_beste_angebote/) webpage by implementing a dynamic filtering mechanism based on user interactions with the category tiles.

## Design

The design for this project can be found on Figma: [Design Link](https://www.figma.com/file/ufDstl93tly8pveDrdAZIF/)

## Changes

The following changes have been implemented to improve the functionality of the webpage:

1. **Default Selection:**

   - By default, all three categories (tiles) are preselected.
   - This ensures that users immediately see the broadest range of products available.

2. **Filter Logic:**

   - When a user clicks on one of the tiles, the green tick disappears, indicating the deselection of that category.
   - The page results dynamically adjust based on the selected categories, implementing an adaptive filter logic.

3. **Total Products Count:**
   - The total count of products found for the search adapts according to the user's selection in the tile segment.
   - This provides users with real-time feedback on the impact of their category selections on the available products.
