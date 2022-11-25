
# Postcards from the Metaverse

A system for saving and navigating towards locations in an x3d environment for use in an extended metaverse.

## Design Implementation

  - Bookmarks stored in localStorage

### Bookmark Format

  ```
  {
    "id": num,
    "title": "string",
    "thumbnail": "url",
    "location":
    {
      "x": num,
      "y": num,
      "z": num
    },
    "orientation":
    {
      "x": num,
      "y": num,
      "z": num,
      "r": num
    },
    "description": "string",
    "link": "url"
  }
  ```
