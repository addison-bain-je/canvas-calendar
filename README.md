# canvas-calendar
Calendar View on Canvas App

Calendars are a common feature in collaborative-type apps, where teams use this to share events, schedule resources and employees to track work hours. However, there is no out-of-the-box Calendar screen component available in canvas app.

Here, I have created a basic calendar view with nested galleries and some custom logic, and functionalities to add/update/remove events on the calendar. 
The app package can be downloaded from the repo.

Below are screenshots of how it works:

## Calendar View
![CalendarView](https://github.com/addison-bain-je/canvas-calendar/blob/main/1-CalendarView.gif)

## Add Event
![AddEvent](https://github.com/addison-bain-je/canvas-calendar/blob/main/2-AddEvent.gif)

## Edit Event
![EditEvent](https://github.com/addison-bain-je/canvas-calendar/blob/main/3-EditEvent.gif)

## Delete Event
![DeleteEvent](https://github.com/addison-bain-je/canvas-calendar/blob/main/4-DeleteEvent.gif)

## Data Source
The backend data source is a SharePoint List named ```SampleEventsList``` consisting of these columns:
| Column Name       | Data Type |
| :---------------- | ------:   |
| Title             | Single line of text    |
| StartDateTime     | Date & Time            |
| EndDateTime       | Date & Time            |
| Description       | Multiple lines of text |


Credits:  
[matthewdevaney-1](https://www.matthewdevaney.com/make-a-calendar-in-power-apps-part-1/)  
[matthewdevaney-2](https://www.matthewdevaney.com/make-a-calendar-in-power-apps-part-2/)
