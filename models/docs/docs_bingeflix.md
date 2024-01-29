# Bingeflix Docs
This file contains doumentation for Bingeflix data sources.

## Users
This section contains documentation from the Bingeflix Users table.

{% docs bingeflix_column_user_id %}
The unique identifier of the Bingeflix user. 
{% enddocs %}

{% docs bingeflix_column_created_at %}
Timestamp of user creation time.
{% enddocs %}

{% docs bingeflix_column_phone_number %}
User's phone number
{% enddocs %}

{% docs bingeflix_column_deleted_at %}
 When the user's account was deleted (This is NULL if the account is not deleted.)
{% enddocs %}

{% docs bingeflix_column_username %}
Username used for login. 
{% enddocs %}

{% docs bingeflix_column_name %}
User's full name.
{% enddocs %}

{% docs bingeflix_column_sex %}
 User's sex at birth.
{% enddocs %}

{% docs bingeflix_column_email %}
 User's email.
{% enddocs %}

{% docs bingeflix_column_birthdate %}
User's birthdate. 
{% enddocs %}

{% docs bingeflix_column_region %}
State or region the user resides in.
{% enddocs %}

{% docs bingeflix_column_country %}
Country the user resides in.
{% enddocs %}



## Subscriptions

{% docs bingeflix_column_subscription_plan_id %}
The unique identifier of the subscription plan.
{% enddocs %}


{% docs bingeflix_column_starts_at %}
When the subscription plan starts.
{% enddocs %}

{% docs bingeflix_column_ends_at %}
When the subscription plan ends (The value is NULL if the subscription plan has auto-renew turned on/does not have a defined end date.)
{% enddocs %}

{% docs bingeflix_column_subscription_id %}
The unique identifier of the subscription.
{% enddocs %}


## Subscription Plans


{% docs bingeflix_column_plan_name %}
The name of the subscription plan.
{% enddocs %}

{% docs bingeflix_column_pricing %}
The price of the subscription plan per payment period.
{% enddocs %}

{% docs bingeflix_payment_period %}
The cadence of the payment period for the subscription plan (e.g., monthly, annually)
{% enddocs %}


## Events

{% docs bingeflix_column_session_id %}
The unique identifier of the session in the Bingeflix application.
{% enddocs %}

{% docs bingeflix_column_created_at_event %}
When the event was logged
{% enddocs %}


{% docs bingeflix_column_event_name %}
Name of the event.
{% enddocs %}

{% docs event_id %}
Unique identifier of the event.
{% enddocs %}

## Ads

{% docs bingeflix_column_ad_date %}
When the ad campaign was served
{% enddocs %}

{% docs bingeflix_column_campaign_id %}
Campaign id for the ad campaign.
{% enddocs %}

{% docs bingeflix_column_spend %}
Amount spent on ad campaign.
{% enddocs %}

{% docs bingeflix_cpm %}
Cost per 1,000 ad impressions.
{% enddocs %}

{% docs bingeflix_column_ctr %}
Average click through rate on ads served.
{% enddocs %}
