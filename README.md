# F-DateTimeRangePicker
## Date Time Range Picker for Flutter

![](/screenshots/sc1.png)

Sample:
~~~~
import 'package:f_datetimerangepicker/picker.dart';

DateTimeRangePicker(
    startText: "From",
    endText: "To",
    interval: 5,
    initialStartTime: DateTime.now(),
    initialEndTime: DateTime.now().add(Duration(days: 20)),
    mode: DateTimeRangePickerMode.time,
    onConfirm: (start, end) {
        
    }).showPicker(context);
~~~~