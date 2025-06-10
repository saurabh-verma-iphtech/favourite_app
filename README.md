# ❤️ Favourite App — Search & Mark Your Favorites 🌟

Favourite App is a Flutter mini-project that allows users to add items, search through them, and mark or filter their favorites using Riverpod for state management.


# 🌟 Project Highlights

# 🔍 Search Functionality

◉ Real-time filtering as you type in the search bar.

◉ Case-insensitive matching on item names.


# 🌟 Favourite Management

◉ Mark items as favorite with a popup menu selection.

◉ Filter view to show all items or only favorites.


# 🛠 State Management with Riverpod

◉ favouriteProvider (StateNotifierProvider) storing:

◉ allItems: the complete list of items.

◉ filteredItems: list shown based on search and filter.

◉ Methods:

addItem(): appends a new item with a default name and favourite=false.

filterList(String query): updates filteredItems by search term.

favourite(String filterType): toggles between showing All or only items marked favorite.

◉ UI rebuilds automatically on state changes.

◉ favouriteProvider (StateNotifierProvider) holding the full list and filtered list of items.

◉ Methods: addItem(), filterList(String query), favourite(String filterType).

◉ UI automatically updates on state changes.


# 🎨 User Interface

◉ AppBar with title “Favourite App” and popup menu (All/Favourite filter).

◉ Search Bar with TextField for input and outlined border.

◉ ListView displaying filteredItems with a heart icon indicating favorite status.

◉ FloatingActionButton to add new items to the list.


# 🧰 Tech Stack

    Category                     Tools & Libraries

    Framework                    Flutter, Dart

    State Management             Riverpod (flutter_riverpod)

    UI Components                Material Widgets (AppBar, ListView, TextField, PopupMenuButton, FAB)


# 🎞️ GIF:

![Workflow GIF](https://i.imgflip.com/9wsi5z.gif)
