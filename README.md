{
	"file": "data/movies/movies.csv",
	"name": "Movies Genres",
	"header": 0,
	"separator": ";",
	"skip": 0,
	"meta": [
		{ "type": "id", "index": 0, "name": "Name" },
		{ "type": "integer", "index": 1, "name": "Release Date" },
		{ "type": "float", "index": 19, "name": "Average Rating", "min": 1, "max": 5 },
		{ "type": "integer", "index": 20, "name": "Times Watched" }
	],
	"sets": [
		{ "format": "binary", "start": 2, "end": 18 }
	],
    "author": "grouplens",
    "description": "MovieLens ratings dataset, curated and filtered by Alsallakh.",
    "source": "http://grouplens.org/datasets/movielens/"
}
