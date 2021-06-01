# Simple Alarm Clock

The idea is a super awesome idea from my lovely husband (Front-end Developer): to create an alarm clock and get a summary of what has been selected.

#### Main functionalities(inputs):

* The alarm clock spreads on 5 days of the week: Monday to Friday.
* by default, no alarm is selected for any day
* It's possible to select an alarm for: 7am or 8am; or no alarm.

#### Results (outputs):

* A list containing the days of the week with active alarms `alarms are active on the following days: {list of days}`. If no alarms are active it says `no alarms are active this week.`
* The number of alarms happening at 7am.
* The number of alarms happening at 8am.
* a summary of everything happening on the 5 days written as such:

```
on {day}, there is no active alarm.
// or
on {day}, the alarm will ring at {chosen time}.
```

#### Part II:

Once all of the above have been done, we want to add a `it's a holidays week` select that links to a boolean. The default value will be `false`.
* If it's a holidays week, we don't work: all alarms are disabled and outputs are updated accordingly.
* If unselected, then alarms are enabled again and outputs are updated accordingly.

#### The goal of the exercise:

Learn javaScript and as such use all of the below:
* the reduce method
* the map method
* the filter method
* if-statements