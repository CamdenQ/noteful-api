# Noteful API

API for Noteful client hosted at https://noteful-client-tawny.vercel.app/

## Endpoints

### /api/notes

get request returns all notes

post adds note from body to list (requires note_name, content, and folder_id keys in body)

### /api/notes/:id

get request returns note with matching id

delete request deletes note with matching id (no data returned)

patch request accepts note body and updates note with matching id (requires note_name, content, and folder_id keys in body)

### /api/folders

get request returns all folders

post adds folder from body to list (requires folder_name key in body)

### /api/folders/:id

get returns folder with matching id

delete request deletes folder with matchign id (no data returned)

patch request accepts folder body and updates folder with matching id (requires folder_name key in body)
