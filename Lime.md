# Lime Endpoints
**Base URL**: `https://web-production.lime.bike/api/rider`

Get Scooter Locations: `/v1/views/map`

Ring Vehicle: `/v1/bikes/<ET-ID>/ring`

User Info: `/v1/user`

Create Reservation: `/v1/trips/create_reservation`

Cancel Reservation: `/v1/trips/<unknown-id>/cancel_reservation` This was the ID that the app created to control the scooter: Z4MGPMLSUNPF7 - Possibly the Scooter S/N.

Active Trip Info: `/v1/views/in_trip`

## Juicer Endpoints

**Base URL**: `https://juicer.lime.bike/api/rider`

Unlock a Lime: `/v1/juicer/tasks/<task ID>/start/`

View Collected Scooters: `/v1/juicer/views/collected/`

Get Info about a specific scooter:`/v2/juicer/bikes/available?plate_number=<6-character-plate-number>`

User Juicer Info: `/v2/juicer/views/bootstrap/`

Pickup cap progress info: `/v1/juicer/views/juicer_level_progress`

Tell if a Juicer has overdue Limes: `/v1/juicer/scooter_charge_tasks/juicer_has_overdue_limes`

Amount pending for completed tasks: `/v1/juicer/views/potential_payout`
