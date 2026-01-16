# Fairmont Apartments Website

Homepage for The Fairmont Apartments, managed by Eugene's mom Larisa Sandugey.

## Property Details

<property>
  <address>16000 Sherman Way, Van Nuys, CA 91406</address>
  <phone>(818) 782-1600</phone>
  <manager>Larisa Sandugey</manager>
  <management_company>LBPM</management_company>
  <built>1985</built>
  <units>101</units>
  <stories>3</stories>
  <neighborhood>Lake Balboa / Van Nuys</neighborhood>
</property>

## Units & Pricing

<units>
  <types>1 BR, 2 BR</types>
  <sqft>700-900</sqft>
  <rent_starting>$2,050/month</rent_starting>
  <security_deposit>~$1,850</security_deposit>
  <application_fee>$40/applicant</application_fee>
</units>

## Amenities

<unit_features>
- Central A/C & Heat
- Tile Fireplace
- Hardwood/Laminate Floors
- Private Balcony or Patio
- Walk-in/Mirrored Closets
- Dishwasher & Garbage Disposal
- Gas Stove & Oven
</unit_features>

<community_features>
- Swimming Pool
- Spa / Hot Tub
- On-Site Laundry
- BBQ Grill Area
- Elevator
- Gated Entrance & Parking
- On-Site Manager
- Smoke-Free
</community_features>

<utilities_included>Water, Sewer, Trash</utilities_included>

## Pet Policy

<pets>
  <allowed>Cats only (no dogs)</allowed>
  <deposit>$300</deposit>
  <limit>2 cats per unit</limit>
</pets>

## Nearby Locations

<nearby>
  <parks>
    - The Japanese Garden (2.9 mi)
    - Lake Balboa Park (nearby)
    - Sepulveda Wildlife Reserve (3.3 mi)
  </parks>
  <shopping>
    - Airport Plaza (0.7 mi)
    - Sherman Way Shops (0.9 mi)
    - Sherman Sepulveda Center (1.2 mi)
  </shopping>
  <transit>
    - Van Nuys Metrolink (2.9 mi)
    - Bob Hope Airport (7.0 mi)
    - North Hollywood Metro (7.9 mi)
  </transit>
  <education>
    - Valley College (5.4 mi)
    - Cal State Northridge (5.7 mi)
    - Pierce College (7.1 mi)
  </education>
</nearby>

## Rental Listing URLs

<listings>
  <apartments_com>https://www.apartments.com/fairmont-apartments-van-nuys-ca/9f990w7/</apartments_com>
  <apartment_finder>https://www.apartmentfinder.com/California/Van-Nuys-Apartments/Fairmont-Apartments</apartment_finder>
  <zillow>https://www.zillow.com/apartments/van-nuys-ca/fairmont/5XjSc2/</zillow>
  <trulia>https://www.trulia.com/building/fairmont-16000-sherman-way-van-nuys-ca-91406-1001482580</trulia>
  <hotpads>https://hotpads.com/fairmont-van-nuys-ca-91406-skfr1z/pad</hotpads>
  <apartment_guide>https://www.apartmentguide.com/apartments/California/Van-Nuys/Fairmont/lnp001E000000nyeA4IAI/</apartment_guide>
  <apartment_ratings>https://www.apartmentratings.com/ca/van-nuys/fairmont-apartments_818782160091406/</apartment_ratings>
</listings>

## Project Structure

```
/home/echo/projects/fairmont/
├── index.html          # Main homepage
├── larisa.png          # Manager headshot
├── images/             # Property photos (to be added)
└── CLAUDE.md           # This file
```

## Design System

<design>
  <aesthetic>Mid-century California modernism, poolside luxury</aesthetic>
  <fonts>
    - Display: Fraunces (serif, weight 500-600)
    - Body: Outfit (sans-serif, weight 300-500)
  </fonts>
  <colors>
    - Terracotta: #c4633a (primary accent)
    - Midnight: #1a1a2e (dark backgrounds)
    - Pool: #4a9b9b (teal accent)
    - Cream: #f5f0e8 (light backgrounds)
    - Sand: #d4c5a9 (secondary text)
  </colors>
</design>

## Local Development

Server runs on port 11849:
```bash
cd /home/echo/projects/fairmont
python3 -m http.server 11849 --bind 127.0.0.1
```

## Future Ideas

- Add property photo gallery
- Set up Cloudflare tunnel for public access
- Add contact form
- Virtual tour integration
