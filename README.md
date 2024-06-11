# filterplugins
Ansible filterplugins.  

Add these to you ansible projects to extend your jinja filters

I'm open for pull requests, in case people want to share theirs

## date_time_filters.py

- reformat_datetime(input_format, output_format) : reformat date_time ; default fallback to today
- diff_datetime(date_format, date2, date2_format, invert) : get the difference between 2 datetimes (from seconds upto years) ; default fallback to today
- add_time_to_datetime(date_format, add_time, add_type) : add time to a datetime ; default fallback to today

