```dataviewjs
await dv.view("tasksCalendar", {pages: "", view: "week", firstDayOfWeek: "1", options: "style11"})
```

<mark style="background: #FFB86CA6; border-radius: 5px; padding: 10px">Overdue</mark>
```tasks
not done
due before today
```

<mark style="background: #FF5582A6; border-radius: 5px; padding: 10px; color: white">Due today</mark>
```tasks
not done
due today
```
```tasks
done
due today
```

<mark style="background: #ADCCFFA6; border-radius: 5px; padding: 10px">Upcoming</mark>
```tasks
not done
due after today
due before in one week
group by backlink
hide backlink
sort by due date
```
<mark style="background: #D2B3FFA6; border-radius: 5px; padding: 10px">No date</mark>
```tasks
not done
no due date
```
