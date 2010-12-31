-- SUMMARY --

This Drupal module is based on fbconnect-events by katbailey. Unlike katbailey's version, this one depends on Drupal for Facebook. Also unlike the original, it works with Facebook's Graph API. Functionality:
-- for nodes with a CCK field called field_fbeid, it automatically adds event info
-- specifically, it adds a list of facebook users attending the event with profile pics and first name
-- it also adds a link to the facebook event page
-- it also allows logged in facebook users to rsvp to the event (the user has to be logged into facebook and drupal, and have the accounts associated)

-- REQUIREMENTS --

PHP 5.2 or higher
Drupal 6.x
Drupal for Facebook w/ these module enabled:
  -- Facebook API
  -- Facebook Apps
  -- Facebook Connect
  -- User Management
  -- Extended Permissions

Make sure you have events_rsvp permission enabled in the Extended Permissions settings

-- WHY ISN'T THIS ON DRUPAL.ORG? --

I chose not to contribute this module to drupal.org because I think it's more of a beginning of a module -- it doesn't allow for a lot of customization or hooks, and doesn't do some things that a robust Facebook Events module would do -- like provide the ability to create events. But I think it could be a useful starting place for a Drupal for Facebook Events module.

If someone created a module based on this on drupal.org, I'd be happy to help maintain it. 
