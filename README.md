# Resource Booking

## Description

There can be several type of resources available in organization (ex. conference room, cab etc).
Each type of resource can have multiple instance. Requester can make request to book any resource. Then admin will review requests and can approve or reject it according to availability or priority.

### Roles and Responsibility:

1. Admin
   * Dashboard (pending requests)
   * Responsible for create resources(type, instance of each type).
   * Can see available and booked resources. (calendar view).
   * Review booking request. (can accept ,reject or change booking request).
   * Generate reports of resources according to status ( booked,free) or per resource instance.
   * Admin should be able to see past records.
  
2. Resource Admin
   * Each type of resource will assign to different Resource admins. So he is Responsible to manage a particular type of resources. (Accept, reject request)
  
3. Requester
   * Dashboard. (user info, approved bookings, pending bookings)
   * Can see available and booked resources. (calendar view).
   * Make request to book resource.
   * Special request - Let suppose a resource is already booked but other requester’s need is more  important(priority based) then earlier booking. So in that case he can make a special request on booked resource. Cancellation of earlier booking and approval of new booking depends on admin.
  

### Modules
1. Resource creation
2. Authentication ( metacube id’s)
3. Resource booking
4. Calendar view.
5. Reports (Future need)

### Screen Shots:
1. Resources:
    ![resources](https://github.com/gbohra/get-16-booking/blob/master/resources.png)
    
    ![resource info](https://github.com/gbohra/get-16-booking/blob/master/edit_resource.png)
2. Booking:
    ![booking](https://github.com/gbohra/get-16-booking/blob/master/booking.png)

    ![booking_info](https://github.com/gbohra/get-16-booking/blob/master/booking_info.png)
  

