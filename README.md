# ✈️ USA CA Trip Planner

A comprehensive trip planning application for your February trip to Los Angeles, Las Vegas, Palm Springs, Grand Canyon, and San Diego.

## Features

### 🗺️ Interactive Map
- View all your places on an interactive map
- Click markers to see photos and descriptions
- Color-coded markers:
  - 🟢 Green = Completed places
  - 🔵 Blue = Places to visit
  - 🔴 Red = Restaurants
- Add custom places with coordinates

### ✅ To-Do List
- Create and manage trip tasks
- Priority levels (High, Medium, Low)
- Mark items as completed
- Filter by status (All, Active, Completed)

### 📋 Trip Info
- Store flight information (outbound and return)
- Manage hotel bookings with check-in/check-out dates
- Track confirmation numbers and room details

### 🎒 Before Trip
- Individual packing lists for each traveler:
  - Piotr
  - Weronika
  - Magda
  - Marek
  - Przemek
- Track packing progress with checkboxes
- Visual progress indicators

### 💰 Budget Tracker
- Set total trip budget
- Track expenses by category (Food, Transportation, Accommodation, Activities, Shopping, Other)
- Visual charts showing spending by category
- Monitor remaining budget

### 📝 Notes
- Keep trip notes and reminders
- Timestamped entries
- Easy note management

## Getting Started

### Local Development

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the app:
```bash
streamlit run app.py
```

### Deploy to Streamlit Community Cloud

1. Push your code to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Sign in with GitHub
4. Click "New app"
5. Select your repository and set the main file path to `app.py`
6. Click "Deploy"

## Data Storage

The app stores all data in JSON files in the `data/` directory:
- `places.json` - Map locations and attractions
- `todo.json` - To-do list items
- `trip_info.json` - Flight and hotel information
- `packing.json` - Packing lists for each person
- `budget.json` - Budget and expense tracking
- `notes.json` - Trip notes

**Note:** For Streamlit Community Cloud, these files will persist during your session. For permanent storage, consider using a database or cloud storage service.

## Usage Tips

- **Map**: Start by adding your planned destinations. The app includes some default locations to get you started.
- **To-Do List**: Add tasks as you think of them, and mark them complete as you go.
- **Trip Info**: Enter your flight and hotel details as soon as you book them.
- **Before Trip**: Use the packing lists to ensure everyone has what they need.
- **Budget**: Track expenses in real-time during your trip to stay within budget.
- **Notes**: Jot down ideas, restaurant recommendations, or anything else you want to remember.

## Customization

You can easily customize:
- Default places in the map
- Traveler names in the packing lists
- Expense categories
- Map center and zoom level

Edit the `init_default_data()` function in `app.py` to modify defaults.

## Support

Enjoy your trip! 🎉

