# Global-Entry
Code to check whether a Global Entry appointment is available for a particular location.

Appointments for Global Entry are added randomly to the portal and disappear within a few minutes due to the high demand.

As a busy student, I do not have time to check the appointments site every day. Therefore, I built a script to repeatedly call upon the Global Entry schedule API and send me an email if an appointment slot opens up for my particular location.

I'm currently adding the email sending functionality at the moment and trying to come up with a way to check appointments at any location. Unfortunately, I have not found anything yet from the API docs (not publicly accessible) of a hash table which stores all the location IDs and location names. I will investigate into this further as I build out this script.

Run this Python script on your local drive in the background, and if anything opens up, you will receive an email saying that an appointment is available.
