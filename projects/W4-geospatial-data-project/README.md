![portada](https://github.com/ironhack-datalabs/datamad1020-rev/blob/master/projects/W4-geospatial-data-project/portada.jpg)

# GeoSpatial Data Project

## TODO's

You recently created a new company in the `GAMING industry`. The company will have the following scheme:

- 20 Designers
- 5 UI/UX Engineers
- 10 Frontend Developers
- 15 Data Engineers
- 5 Backend Developers
- 20 Account Managers
- 1 Maintenance guy that loves basketball
- 10 Executives
- 1 CEO/President

As a data engineer you have asked all the employees to show their preferences on where to place the new office. Your goal is to place the **new company offices** in the best place for the company to grow. You have to find a place that more or less covers all the following requirements (note that **it's impossible to cover all requirements**, so you have to prioritize at your glance):

- Designers like to go to design talks and share knowledge. There must be some nearby companies that also do design.
- 30% of the company staff have at least 1 child.
- Developers like to be near successful tech startups that have raised at least 1 Million dollars.
- Executives like Starbucks A LOT. Ensure there's a starbucks not too far.
- Account managers need to travel a lot.
- Everyone in the company is between 25 and 40, give them some place to go party.
- The CEO is vegan.
- If you want to make the maintenance guy happy, a basketball stadium must be around 10 Km.
- The office dog—"Pepe" needs a hairdresser every month. Ensure there's one not too far away.

## Help

- Always use standard GeoJSON Point `{ type: "Point", coordinates: [ 40, 5 ] }`
- Create sphere2d index in python with pymongo: `db.collection.createIndex( { <location field> : "2dsphere" } )`
- MongoDB `$near` operator: <https://docs.mongodb.com/manual/reference/operator/query/near/#op._S_near>

## How to deliver the project

- Create a new repo in your github account.
- Do a PR with the link of your repo copy pasted inside `my-project.md` (within the parentheses) on this repo.
- You must justify your decision with a map, use visualization tools like (tableau, folium, cartoframes, etc.)
- Provide `lat` and `long` for the new office proposals.

## Links & Resources

- [https://developers-dot-devsite-v2-prod.appspot.com/maps/documentation/javascript/examples/geocoding-reverse]
- [https://docs.mongodb.com/manual/geospatial-queries/]
- [https://developers.google.com/maps/documentation/geocoding/intro]
- [https://developers.google.com/maps/documentation/geocoding/start]
- [https://data.crunchbase.com/docs]
- [https://developers.google.com/places/web-service/search]
- [https://www.youtube.com/watch?v=PtV-ZnwCjT0]
- [https://developer.foursquare.com/]
- [https://cloud.google.com/maps-platform/places/]
- [https://www.meetup.com/meetup_api/]
