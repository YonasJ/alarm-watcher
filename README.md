# THIS DOES NOTHING YET, I JUST FORKED THIS OTHER PROJECT... THE DESCRIPTION IS WHAT I AM PLANNING.

# Alarm Watcher

This is an On/Off swtich which watches for an input to occur fore more than a specified time, and then turn's it self to on.

For example, you could set a door sensor open to this, and then it will change it's state to ON if the door is open more than the required time. So this could create the effect of "If the door has been open for longer than 30 seconds within 2 minutes, sound the alarm."

## Configuration

### name

Sets the name of the device. This must be unique

### duration

The amount of time, in seconds, before the device will set itself as on.

### interval

The amount of time before it resets its internal timer to 0.
