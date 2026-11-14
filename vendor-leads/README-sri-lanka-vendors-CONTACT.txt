SRI LANKA VENDORS WITHOUT WEBSITE / DOMAIN — CONTACT CSV
=========================================================

FILES
-----
1) sri-lanka-20000-vendors-no-website-CONTACT.csv
   Full island-wide extract: 22,286 named businesses with NO website/domain URL on the map record.

2) sri-lanka-TOP20000-vendors-no-website-CONTACT.csv
   Same data, first 20,000 rows prioritized (phone/email/address first).

3) sri-lanka-COMMERCIAL-vendors-no-website-CONTACT.csv
   Commercial filter (excludes government / banks / educational / NGO-type offices).

4) sri-lanka-vendors-no-website-WITH-PHONE-OR-EMAIL.csv
   Subset with phone or email filled — call/email these first.

IMPORTANT LIMITATION
--------------------
A complete dump of Google Maps / Google Business Profile listings for Sri Lanka
is NOT free. Google does not allow bulk scraping; Places API is paid and rate-limited.
This dataset is the largest open island-wide alternative (OpenStreetMap), with
google_maps_url_by_coords and google_maps_url_by_name columns so you can open
each place on Google Maps and confirm the Google listing / missing website.

COLUMNS (contact-ready)
-----------------------
business_name              - Trading name
primary_category           - shop / amenity / tourism / office / healthcare / craft / leisure
business_type              - Detailed type (clothes, restaurant, shoes, hotel, ...)
brand                      - Brand if tagged
operator                   - Operator if tagged
contact_person             - Usually blank (not published on maps)
primary_phone              - Best phone to dial (phone or mobile or whatsapp)
phone, mobile, whatsapp    - Separate phone fields
email, fax
full_address               - Combined address
addr_housenumber, addr_street, addr_place, addr_suburb,
addr_city, addr_village, addr_district, addr_province, addr_postcode
latitude, longitude
google_maps_url_by_coords  - Open Google Maps at exact pin
google_maps_url_by_name    - Search Google Maps by name + Sri Lanka
opening_hours
facebook, instagram, twitter
has_website                - Always No in this file
has_domain_in_name         - Yes if name itself looks like a domain
website                    - Empty
floor_level, description
country                    - Sri Lanka
source, source_id, osm_url, data_notes

HOW TO USE FOR SALES
--------------------
1. Sort/filter by business_type (clothes, shoes, supermarket, pharmacy, ...).
2. Call rows in WITH-PHONE-OR-EMAIL first.
3. For others, open google_maps_url_by_coords — Google often shows a phone even when OSM does not.
4. Pitch POS + online catalog + stock/delivery to shops without a website.

For a true Google-only "no website" filter at national scale, use Google Places API
(websiteUri empty) or a paid vendor (e.g. SmartScrapers / similar GBP data providers).
