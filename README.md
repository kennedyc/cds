CDs
=========

This is a service for keeping track of a personal CD collection.  It includes:

  - A list of CDs
  - CDs identified by ISBN number
  - Tracks for each CD
  - A list of CDs that contain artists, song names, release dates, titles, or any combination of these parameters
  - A list of genres
  - A concentration of CDs in a specific genre

Attribute values: id, class, name, and rel
-
id
-----------
  - list - Applied to a div tag.  The list of CDs in the collection.
  - genre - Applied to a div tag.  The genre or list of genres in the collection.
  - cd - Applied to a div tag.  A CD and its tracks.
  - track - Applied to a div tag.  A track on a CD.

class
-----------
  - track - Applied to a form tag.  Search for a track.
  - id - Applied to a form tag.  Search for an ISBN number.
  - name  - Applied to a form tag.  Search for a CD title.
  - artist - Applied to a form tag.  Search for an artist.
  - date - Applied to a form tag.  Search for a release date.

name
-----------
  - title - Applied to a form tag.  Add a CD title.
  - ISBN - Applied to a form tag.  Add an ISBN number.
  - create-cd - Applied to a form tag.  Create a CD.
  - create-track - Applied to a form tag.  Create a track.
  - create-genre - Applied to a form tag.  Create a genre.
  - update-track - Applied to a form tag.  Update a track.
  - update-genre - Applied to a form tag.  Update a genre.
  - delete-cd - Applied to a form tag.  Delete a CD.
  - delete-track - Applied to a form tag.  Delete a track.
  - delete-genre - Applied to a form tag.  Delete a genre.
  - id - Applied to a form tag.  Add an ISBN number.
  - name - Applied to a form tag.  Add a CD title.
  - artist - Applied to a form tag.  Add an artist.
  - date - Applied to a form tag.  Add a release date.
  - form - Applied to a form tag.   A form for entering information.

rel
-----------
  - index Applied to an a tag.  A reference to the starting URI for the service.
  - stylesheet - Applied to a link tag.  A link to the CSS stylesheet.
  - genres - Applied to an a tag.  A reference to the list of genres.
  - query - Applied to an a tag.  A reference to the query form.
  - cd - Applied to an a tag.  A reference to a CD.
  - add-cd - Applied to an a tag.  A reference to form for adding CDs.
  - track - Applied to an a tag.  A reference to a track on a CD.

Microdata types and properties used to describe the data
-
itemtype
-----------
  - CollectionPage - http://schema.org/CollectionPage - Indicates the collection or gallery to which the item belongs
  - MusicAlbum - http://schema.org/MusicAlbum - The album to which this recording belongs.
  - MusicGroup - http://schema.org/MusicGroup - The artist that performed this album or recording.
  - MusicRecording - http://schema.org/MusicRecording - A music recording (track), usually a single song.

itemprop
-----------
  - byArtist - The artist that performed this album or recording.
  - genre - Genre of the creative work.
  - name - Name of the creative work.
  - track - A music recording (track)—usually a single song.