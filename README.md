# Hotel_Dashboard
### Mock Dashboard for STAR Metrics

This **Interactive Hotel Dashboard** was created in Quicksight using a mock dataset, generated using Python in VS Code.

### Dashboard Specs
*  The dashboard includes Occupancy Rate with an automatic running line average, an Occupancy Gauge, ADR, RevPAR, and RevExtras over time, and KPIs for Cancellations, Booked Rooms, and Total Charges.
*  By Selecting a date in the Occupancy Rate figure, all other figures will update to match the corresponding data.

### Metrics
The data includes the following metrics:

**Date**: Specific date of the record.

**Hotel_ID**: Identifier for the hotel.

**ADR (Average Daily Rate)**: Average revenue earned from rented rooms.

**Occupancy Rate**: Percentage of occupied rooms.

**RevPAR (Revenue per Available Room)**: Calculated as ADR multiplied by the Occupancy Rate.

**Available Rooms**: Total number of rooms available for booking.

**Booked Rooms**: Total number of rooms booked.

**Cancelations**: Number of canceled bookings.

**No Shows**: Number of guests who did not check-in as expected.

**Deposits**: Total amount of deposits received.

**Customer Type**: Type of customer (e.g., Business, Leisure, Group).

**Stay Length**: Number of nights stayed.

**Total Charges**: Total charges for the stay, calculated as ADR multiplied by Stay Length.

**Market Segment**: Segment of the market from which the booking originated (e.g., Online, Direct, Agent).

**Booking Channel**: Channel through which the booking was made (e.g., Website, Phone, Agent).

**Special Requests**: Number of special requests made by the guest.

**Meal Plan**: Type of meal plan included (e.g., None, Breakfast, Half-board).

**Check-in Day of Week**: Day of the week the guest checked in.

**Advance Booking Days**: Days booked in advance.

**Revenue from Extras**: Revenue generated from extra services like spa, tours, etc.
