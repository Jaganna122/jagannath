1. Layout & Grid System
Class	Meaning	What it Does	Where Used
container	Container	Centers content and sets maximum width for responsive layout	Navbar, About section, Courses section, Footer
row	Row	Creates a flexbox row to hold columns	About section, Courses section
col-md-6	Column Medium (6/12)	On medium+ screens (≥768px), takes 50% width	About section (image & text)
col-md-4	Column Medium (4/12)	On medium+ screens, takes ~33.3% width	Courses cards
g-4	Gutter 4	Adds spacing (gap) between columns in a row	Courses row
align-items-center	Align Items Center	Vertically centers content inside a flex row	About section row

2. Navbar Classes
Class	Meaning	What it Does	Where Used
navbar	Navbar	Main navigation bar structure	Top navigation
navbar-expand-lg	Navbar Expand Large	Expands fully on large screens, collapses on smaller ones	Navbar
navbar-dark	Navbar Dark	Light text color for dark backgrounds	Navbar
bg-dark	Background Dark	Sets dark background color	Navbar & Footer
shadow-sm	Shadow Small	Adds a small box shadow	Navbar
sticky-top	Sticky Top	Keeps navbar fixed at top while scrolling	Navbar
navbar-brand	Navbar Brand	Styles the logo/brand name	"Vedatutor" logo
navbar-toggler	Navbar Toggler	Mobile menu toggle button	Hamburger icon
navbar-toggler-icon	Navbar Toggler Icon	Displays the hamburger lines	Mobile menu
collapse navbar-collapse	Collapse Navbar Collapse	Container for collapsible menu content	Nav items
nav-item	Nav Item	Navigation list item	Menu items (Home, About, etc.)
nav-link	Nav Link	Styles navigation links	All menu links
active	Active	Highlights the current/active page	Home link
dropdown	Dropdown	Enables dropdown menu	Courses menu
dropdown-toggle	Dropdown Toggle	Trigger button for dropdown	Courses link
dropdown-menu	Dropdown Menu	The dropdown list container	Courses items list
dropdown-item	Dropdown Item	Styles individual dropdown links	Web Dev, Graphic Design, etc.

3. Carousel Classes
Class	Meaning	What it Does	Where Used
carousel slide carousel-fade	Carousel Slide + Fade	Enables sliding with fade transition instead of slide	Hero section
data-bs-ride="carousel"	Data Bootstrap Ride	Auto-starts the carousel	Carousel
data-bs-interval="3000"	Data Bootstrap Interval	Changes slide every 3 seconds	Carousel
carousel-inner	Carousel Inner	Container for all slides	Hero slides
ratio ratio-21x9	Aspect Ratio 21:9	Maintains responsive height based on width	Carousel inner
carousel-item	Carousel Item	Defines individual slide	Each slide
active	Active	Makes the first slide visible	First slide
d-block w-100 h-100	Display Block + Full Width/Height	Makes image fill the slide completely	Carousel images
object-fit-cover	Object Fit Cover	Crops image to cover area without distortion	Carousel images
img-fluid	Image Fluid	Makes image responsive (scales with container)	All images
carousel-caption	Carousel Caption	Text overlay on slides	Slide headings & text
text-start	Text Start (Left Align)	Left-aligns text	First slide caption
carousel-control-prev/next	Carousel Control Prev/Next	Previous/Next navigation buttons	Carousel arrows

4. Card Classes (Courses Section)
Class	Meaning	What it Does	Where Used
card	Card	Basic card container	All course cards
card-img-top	Card Image Top	Places image at the top of the card	Course images
card-body	Card Body	Content area inside the card	Course text & button
h-100	Height 100%	Makes card take full height of its column	All cards
text-center	Text Center	Centers text horizontally	All cards
shadow-sm	Shadow Small	Adds small shadow (normal state)	Cards
shadow	Shadow	Medium shadow (you used both – shadow-sm is enough)	Cards (some duplicates)
border-0	Border None	Removes card border	Cards
rounded-4	Rounded 4	Applies larger rounded corners (modern look)	Cards
overflow-hidden	Overflow Hidden	Prevents content (like zoomed image) from overflowing	Cards

5. Button Classes
Class	Meaning	What it Does	Where Used
btn	Button	Basic button styling	All buttons
btn-warning	Button Warning	Yellow/orange button	Most Enroll buttons
btn-dark	Button Dark	Dark gray button	Graphic Design Enroll, Read More
btn-primary	Button Primary	Blue button	Digital Marketing Enroll
btn-secondary	Button Secondary	Gray button	Modal Close button
rounded-pill	Rounded Pill	Fully rounded (pill-shaped) button	All Enroll & some others
px-4	Padding X 4	Adds horizontal padding	Navbar Enroll button

6. Modal Classes
Class	Meaning	What it Does	Where Used
modal fade	Modal Fade	Modal with fade-in/out animation	Signup modal
modal-dialog	Modal Dialog	Centers the modal vertically	Modal
modal-content	Modal Content	Main wrapper for modal content	Modal
modal-header	Modal Header	Top section with title and close button	Modal title
modal-title	Modal Title	Styles the modal heading	"Sign Up / Enroll Now"
btn-close	Button Close	Close (X) button	Modal close
data-bs-dismiss="modal"	Data Bootstrap Dismiss	Closes the modal when clicked	Close buttons
modal-body	Modal Body	Main content area (form)	Form
modal-footer	Modal Footer	Bottom area for action buttons	Submit & Close
data-bs-toggle="modal"	Data Bootstrap Toggle Modal	Opens the modal on click	All Enroll buttons
data-bs-target="#signupModal"	Data Bootstrap Target	Specifies which modal to open	Enroll buttons

7. Form Classes (Inside Modal)
Class	Meaning	What it Does	Where Used
mb-3	Margin Bottom 3	Adds spacing between form fields	All form groups
form-label	Form Label	Proper styling for input labels	All labels
form-control	Form Control	Styles text inputs and textarea	Name, Email, Phone, Message
form-select	Form Select	Styles dropdown select	Course selection

8. Typography & Spacing Utilities
Class	Meaning	What it Does	Where Used
fw-bold	Font Weight Bold	Makes text bold	Headings, titles
fw-semibold	Font Weight Semibold	Slightly bold text	Nav links
text-warning	Text Warning	Yellow/orange text color	Brand name
text-light	Text Light	Light gray text (good on dark bg)	Footer text
my-5	Margin Y 5	Top & bottom margin	Sections (About, Courses)
mb-4	Margin Bottom 4	Bottom margin	Headings
py-4	Padding Y 4	Top & bottom padding	Footer
text-center	Text Center	Centers text	Footer, Courses heading
rounded	Rounded	Default rounded corners	About image






























































