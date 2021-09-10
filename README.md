# SF Cons DB

SF Cons DB is a data file of upcoming science fiction and fantasy conventions. It serves as a mock database consumed by a frontend application via [JSON Server](https://github.com/typicode/json-server).

## Usage

### Get Events

Retrieve a listing of upcoming science fiction and fantasy conventions.

#### Endpoint

```
GET /events
```

#### Example Response

```
[
    {
        "id": "100121cc",
        "title": "Capclave 2021",
        "description": "Literary convention focusing on the short fiction form",
        "fullDescription": "Capclave is a small relaxed literary convention with a program that usually focuses on the short fiction form. Our Guests of Honor and other notable authors, editors, artists, and fans of the short fiction form will explore the creation and enjoyment of short fantasy and science fiction genre stories.",
        "date": "October 1-3, 2021",
        "location": "Rockville, MD",
        "url": "https://www.capclave.org"
    },
    {
        "id": "111921pc",
        "title": "Philcon",
        "description": "The world's first and longest-running conference on science fiction, fantasy, and horror",
        "fullDescription": "Started in 1936, Philcon features cutting-edge programming about literature, art, television, film, anime, comics, science, gaming, costuming and cosplay, music, and other topics of interest to fans of sci-fi, fantasy, and horror. We will also have many other attractions, such as our awesome Art Show and Auction; a Vendors Room full of unique merchandise; Children’s/Family programming; a full-featured Tabletop Gaming room; our Writer’s Workshop (featuring professional authors and editors); Concerts; Dorian’s Dance Party, our Masquerade/Costume Competition, and more!",
        "date": "November 19-21, 2021",
        "location": "Cherry Hill, NJ",
        "url": "https://philcon.org"
    },
    …
]
```

### Get Single Event

Retrieve a single SFF convention.

#### Endpoint

```
GET /events/:id
```

#### Example Response

```
{
    "id": "100121cc",
    "title": "Capclave 2021",
    "description": "Literary convention focusing on the short fiction form",
    "fullDescription": "Capclave is a small relaxed literary convention with a program that usually focuses on the short fiction form. Our Guests of Honor and other notable authors, editors, artists, and fans of the short fiction form will explore the creation and enjoyment of short fantasy and science fiction genre stories.",
    "date": "October 1-3, 2021",
    "location": "Rockville, MD",
    "url": "https://www.capclave.org"
}
```
