# MakersBnb

![Homepage](https://i.gyazo.com/f139543830828125a449553a73d90427.jpg)

### A Ruby and Sinatra Airbnb clone built in 5 days. Uses raw SQL to interact with a Postgresql database, and Bootstrap for styling. Supports signing up as a host or guest, where hosts can post bnb listings and guests can book them (hosts can also book them too).

# Demo

### Sign up

![Host sign up](https://i.gyazo.com/15142bc7b4d79a1e237b9384e94ce592.png)

### Initial host dashboard

![Host empty dashboard](https://i.gyazo.com/721c27f091dd7a089988ea8573646142.png)

### Host create listing form

![Host create listing](https://i.gyazo.com/0c7e170dff8617c88b0dc4c279a12a08.png)

### Host dashboard shows that hosts' listings

![Host dashboard listing](https://i.gyazo.com/3c0b7a853bcc87b53c060b6e66fc7a46.png)

### Search page with empty fields shows all bnbs

![Empty search](https://i.gyazo.com/5b0eadb0ce8f793fdda69d7ed0917cba.gif)

### Search is case insensitive

![Case insensitive search](https://i.gyazo.com/e5e13b20a7ceb03307bba0dd748a6c57.gif)

### Search accurately returns results e.g. changing price, and can have any fields empty

![Search demo](https://i.gyazo.com/72ff90faea86cd6c6b416c4b2f4d5b5f.gif)

### Clicking on a listing goes to it's page, where you can see a calender with the its' bookings

![Listing page empty](https://i.gyazo.com/58e67c95baf160df66c27cae4a3d9178.gif)

### User books a bnb and gets a confirmation message

![Booking confirmation](https://i.gyazo.com/8c26bf2c0b69a9c7b34f0ef4d0d02854.gif)

### The calendar now updates to show this date period blocked out

![Booking calendar](https://i.gyazo.com/96cf0d64d996ffcc49b0924cd1aafe0d.png)

### This bnb now doesn't appear when you search for a date and it overlaps with an existing booking

![Booking search](https://i.gyazo.com/1ceddf2216903418295e40f1c1484dbc.gif)

### Booking is shown on guest dashboard

![Guest dashboiard](https://i.gyazo.com/fc4a3a577d3dd572bdea2deac863b1dd.jpg)

### Host dashboard shows the bookings at their bnb

![Host dashboard booking](https://i.gyazo.com/7c6893fa554ad8f06ee51f9ea04a9fa2.jpg)

# Setup

If you wish to use this application:

```
git clone https://github.com/ConorButler/makers-bnb.git
cd makers-bnb
bundle
rackup
```

Then go to http://localhost:9292 on your browser

# User stories

```
As a host
So that I can rent out my property,
I want to be able to signup as a host. ✓

As a host
So that I can rent out my property,
I want to be able to create a bnb. ✓

As a host
So that I can modify my bnbs,
I want to be able to delete or edit my bnbs. ✓

As a host,
So that I know when my property is being booked,
I want to be able to see a list of bookings for my bnb. ✓

As a guest
So that I can book a property,
I want to be able to sign up as a guest. ✓

As a guest,
So that I can book a property,
I want to see all the bnbs. ✓

As a guest,
So that I can book a property on a certain date or location,
I want to be able to filter my search of bnbs. ✓

As a guest,
So that I can book a property,
I want to be able to create a booking. ✓

As a guest,
So that I remember my bookings,
I want to be able to see a list of my bookings. ✓

As a guest,
So that I can modify my bookings,
I want to be able to delete or edit my bookings. ✓

As a user,
So that no one else can use my account,
I want to be able to log in and log out. ✓

```
