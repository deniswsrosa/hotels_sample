# Sample Database of Hotels

This database has 8076 hotels, each document is similar to the following

```
{
  "activity": "sleep",
  "address": "Calle Cantarranas 47",
  "alt": null,
  "checkin": null,
  "checkout": "11:00",
  "content": "Great location in the historic center, budget, basic, no frills but clean, free kitchen, wireless, promotions and the best rooftop in Guanajuato. This is a legally-registered hostel in the city and the owner, Olivia Machuca, is the president of the Associacion of Mexican Hostels. Their goal is to provide a professional and friendly service to the visitors. La Casa del Tío is always recommended in travel guides such as ''Lonely Planet'', ''Rough Guides'' and ''Let's Go'' among others. The laundry machine they offer on the website doesn't work.",
  "directions": null,
  "email": "lacasadeltio@hotmail.com",
  "fax": null,
  "geo": {
    "lat": 21.01486,
    "lon": -101.25176
  },
  "hours": null,
  "id": 10580,
  "image": null,
  "name": "La Casa del Tío",
  "phone": "+52 473 733 9728",
  "price": "US$15-40",
  "title": "Guanajuato",
  "tollfree": null,
  "type": "hotel",
  "url": "http://www.lacasadeltio.hostel.com/"
}
```

Note that the field **price** has no standard format.


##How to import this dataset in Couchbase

1) Create a new bucket( Eg. a new bucket called **test**)
2) Unzip the hotels.json.zip in a directory
3) Go to the directory where Couchbase was installed, on mac it is usually at `/Applications/Couchbase Server.app/Contents/Resources/couchbase-core/bin`
