# Overview
The Qonfi product finder for Magento 2 extension provides two custom widget templates that allow you to easily integrate Qonfi into your store. The extension places the required vendor scripts into the head of your site and offers flexible widget configuration options, including display type and WYSIWYG content support.

# Features
Two custom widget templates for Qonfi integration.
Automatic inclusion of the Qonfi vendor script in the head.
Widget options for UUID, display type, and custom WYSIWYG content.
Supports popup, inline, and sidebar display modes.


1. Qonfi WYSIWYG Widget
Qonfi wysiwyg UUID	int	Unique identifier for the Qonfi WYSIWYG instance
Type - select- Display type: popup, inline, or sidebar
WYSIWYG field - text - Custom content to be displayed within the widget, you can include widgets, blocks or write something

2. Qonfi Widget Default
Qonfi UUID - int - Unique identifier for the Qonfi block
Type - select - Display type: popup, inline, sidebar
Title - text - Block title
Content text - text - Main content text
Button text - text - Text for the action button
Background Color - color - Block background color
Text Color - color - Primary text color
Button Text Color - color - Button text color
Button Background Color - color - Button background color

# Usage
In the Magento Admin Panel, navigate to Content > Widgets.
Add a new widget and select your desired Qonfi widget template.
Configure the widget options as needed.
Assign the widget to store views and pages.

# Including the Vendor Script
The extension automatically places the required Qonfi vendor script into the head of your site, ensuring that the widget functions correctly without manual script management.