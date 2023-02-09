# Train_Schedule

**Train Schedules** are used to instruct non-player Train conductors.

## Train Schedule

### Renewable

Yes

### Stackable

Yes (64)

## Contents

- 1 Obtaining
    - 1.1 Crafting
- 2 Usage
    - 2.1 Programming
        - 2.1.1 Station Recognition
        - 2.1.2 Conditions
    - 2.2 Automatic Schedule Changing
- 3 History

## Obtaining[]

### Crafting[]

## Usage[]

Right-click a valid conductor with a schedule to give it to them. A conductor must either be a mob Seated directly in front of Train Controls on an assembled Train or a Blaze Burner positioned similarly.

### Programming[]

The Train will continue past Station East at 20% max speed if a player is seated AND the cargo has been inactive for 5 seconds, OR at 8:00 AM daily.

Right click with the Schedule in hand to open the interface. 3 types of commands can be added.

- Travel to Station - Navigate to a specified Train Station.
- Update Schedule Title - Name of route as displayed by the Train Station summary in the Display Link.
- Limit Max Speed - Change max speed when traveling to a station.

### Station Recognition[]

Train Stations can be specified by simply typing their name in the appropriate field. Train Stations can be given unique names in their own interface. Stations will show up in the Schedule’s interface regardless of if they’re connected to the same rail network. If multiple stations have the same name, the conductor will choose the nearest accessible and unoccupied station of them. A conductor will not navigate to a different station that has the same name as the one they’re currently at.

“*” can be used as a wildcard character. If a Train is scheduled to arrive at Station *, it can arrive at either Station 1 or Station 2 depending on which is more accessible.

### Conditions[]

The Travel to Station command allows for multiple AND or OR conditions to be added. All of these conditions can be checked regardless of if the chunk is loaded, though Cargo conditions may not be met as unloaded chunks cannot change the Train’s cargo. The Train will continue to the next station if or after these conditions are met:

- Scheduled Delay - Wait for 0-120 ticks, seconds, or minutes.
- Time of Day - Beginning at an in-game hour, and repeating at a specified interval (Daily, every 12 hours, from every 6 hours to hourly, or every 45, 30, or 15 minutes)
- Fluid Cargo Condition - If the Train has more than, less than, or exactly a specified amount of a fluid. Filters optional.
- Item Cargo Condition - If the Train has more than, less than, or exactly a specified amount of items or stacks of items. Filters optional.
- Redstone Link - If a Redstone Link sends or does not send a signal on the specified Frequency. This is checked globally, regardless of the link’s range. No extra Redstone Links required.
- Players Seated - If the Train has exactly or at least a specified amount of players seated at any point.
- Cargo Inactivity - If there are no changes to Train Cargo within 0-120 ticks, seconds, or minutes.
- Chunk Unloaded - When arriving at a station in an unloaded chunk, the Train will continue despite it being unloaded.
- Station Powered - If the station the Train is at is powered by Redstone.

Train Schedules can be set to loop infinitely.

### Automatic Schedule Changing[]

Upon stopping at a station, if a Schedule is input to the station, the contents will be copied to the conductor’s current schedule. The schedule itself will remain at the station.

## History[]

- 0.5: Introduced.