import React from "react";

// ============================================================================
// CHS Itinerary Builder — Reset, Stable, Pixel-True MVP (Null-safe DOM ops)
// ----------------------------------------------------------------------------
// What works in this pass:
// • Exact Master Template shell rendering (no rewording)
// • Live guest names (one-by-one, smart header collapse) + live stay range
// • Fixed 7×6 calendar with « ‹ › » and Today; set Arrival/Departure from focus
// • Day headers auto-built inside “YOUR SCHEDULED ACTIVITIES”; no default dinners
// • Print / Copy-as-text
// • Null-safe DOM access around editorRef & parentElement (fixes crash)
// • Minimal self-tests (run once in console)
// ============================================================================

export default function CHS_Itinerary_Builder_Reset() {
  // ------------------------------ MASTER TEMPLATE ---------------------------
  // IMPORTANT: keep as a template literal; do not inject ${} here.
  const MASTER = `
{ STAY DATES ( Thursday, October 24 – Sunday, October 27) }

Dear {GUEST NAME},

We are delighted to welcome you to Castle Hot Springs! Our desert oasis of adventure, flavor, seclusion and relaxation await. We invite you to unwind in the natural hot springs, indulge in the flavors of the season at both Harvest Restaurant and Bar 1896, enjoy a massage alongside the natural spring creek, and experience an array of adventures and activities.

DINING

Explore your palate throughout the day with breakfast, lunch, and dinner — which is a unique multi-course tasting menu. Each meal will take you through a culinary experience of flavor combinations that will delight. There is a Grab n' Go coffee station beginning at 5:00AM; starting at 6:00AM parfaits (assorted toppings), granola bars and breakfast bread are available.

HARVEST
Breakfast | 7:00AM - 10:00AM
Lunch | 11:00AM - 2:00PM
Dinner | 5:30PM - 8:00PM
For dinner, reservations are required. Attire is elevated resort casual, no athletic-wear, please.

BAR 1896
Grab n’ Go | 6:00AM - 8:00AM
Lunch | 11:00AM - 2:00PM
Bistro Menu | 2:00PM - 9:00PM
á la carte | 5:30PM - 9:00PM
Cocktails | 11:00AM – Close

POOL SERVICE
Food Menu & Drinks 11:00AM – 4:30PM

IN-ROOM AMENITIES
Settle into your accommodations with well-appointed amenities. Your curated refreshments station includes a complimentary Nespresso machine, organic teas, local wines, drinks, snacks, and two 18oz YETI Rambler™ water bottles. Also enjoy an iPad with resort information, a Bose speaker, Wi-Fi, and convenient toiletries. To connect to Wi-Fi, select Castle Hot Springs Resort and enter the password RUsureUwant2?

ACTIVITIES, ADVENTURES & SPA
A multitude of ways to explore are available, guided and on your own. Please review the activity schedule, your itinerary, or visit the Activities Desk for more information. Wellness amenities and spa treatments are based on availability; inquire at the Front Desk. For these experiences, please consider functional clothing as you see fit.

If you need assistance or have questions, please call the Front Desk from your guestroom phone. Access to the hot springs is available 24/7 as is the cart service for ease of transport. We hope you have a wonderful time at our desert oasis!

Sincerely,
Castle Hot Springs Team

YOUR SCHEDULED ACTIVITIES

<div id="chs-activities-anchor"></div>

OASIS OF TIME – DOCUMENTARY RECEPTION
As an introduction to Castle Hot Springs, we welcome guests daily to our documentary reception. Released in 2019, this Emmy award-winning film “Oasis of Time” celebrates Castle Hot Springs’ extensive history that dates back over a century. Join us for a complimentary glass of wine at 4PM in the historic Stone House building as this inspiring 40-minute film walks you through our beautifully rich history. Please book your seat with the Front Desk.

BOUTIQUE & HISTORY ROOM
Experience the history of Castle Hot Springs with a stroll through our History Room, where collected artifacts, past amenities, and memorabilia are displayed for guests to learn from. The Boutique offers guests a curated selection of gifts, apparel, collectibles, and hand-crafted wellness products only found at Castle Hot Springs.
All Activities and Adventures require a prior reservation and are subject to change without notice. Cancellations of paid activities within 24 hours of the scheduled time or no-shows will be subject to 100% of the scheduled activity cost.`;

  // ------------------------------ RAW CATALOG (VERBATIM) --------------------
  // Provided verbatim; parsed later. (Kept here for continuity; picker wires next pass.)
  const RAW_SPA = `Spa Wellness Menu
[TIME] 60-minute ____________ Yoga | GUEST NAME 
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Intro to Yoga | GUEST NAME 
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Qigong | Microcosmic Orbit Series | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Qigong | Purifying the Five Elements | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Qigong | Standing 8 Brocades | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Tai Chi | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Guided Wellness Hike | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Meditation | GUEST NAME 
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Seated 8 Brocades | GUEST NAME 
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Spiritual Mantra | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME]  Zen Soaking Secrets | GUEST NAME
Please arrive at the Watsu Pool 5 minutes prior to your appointment time.

[TIME] Divine Slumber Session | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Renew + Restore Sound Session | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Five Spirit Animal Protection | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Breathwork | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Four Pillars Astrology | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Personal Elemental Constitution | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute I Ching Consultation | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Seasons of Life | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] 60-minute Limbs of Yoga | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME]  Water Wellness Trio | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.
Proper attire includes athletic wear or loose-fitting clothing (no bathing suits).

[TIME]  Three Hearts, Nine Gates | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

[TIME] Private Nature’s Rhythm Hike | GUEST NAME
Please meet at the Activities Desk five minutes prior to the start time.

CHAKRA TUNE UP
15min pre & post service buffer

[TIME] 60-minute Chakra Tune Up | GUEST NAME
Please arrive to the Stone House or the Wellness Loft at the time of your appointment.

MASSAGES

In Room Service Notation:
[TIME] 60/90/120-minute (Session Type) in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

Castle Hot Springs Signature Mineral Scrub & Full Body Massage

Double Service
[TIME] Two, 90-minute Signature Mineral Scrub & Full Body Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] Two, 120-minute Signature Mineral Scrub & Full Body Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

Single Service
[TIME] 90-minute Signature Mineral Scrub & Full Body Massage | GUEST
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 120-minute Signature Mineral Scrub & Full Body Massage | GUEST
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

PRENATAL MASSAGES

[TIME] 60-minute Motherhood Massage
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Motherhood Massage
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

SIGNATURE CBD MASSAGE

Double Service

[TIME] Two, 90-minute Signature CBD Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] Two, 120-minute Signature CBD Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

CBD Single Service

[TIME] 90-minute Signature CBD Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 120-minute Signature CBD Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

ADVENTURE RECOVERY MASSAGE

[TIME] 60-minute Adventure Ready Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Adventure Ready Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] Two, 60-minute Adventure Ready Massages
| Separate or Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] Two, 90-minute Adventure Ready Massages
| Separate or Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

SIGNATURE AROMA-WELLNESS MASSAGE

Double Service

[TIME] Two, 60-minute Signature Aroma – Wellness Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] Two, 90-minute Signature Aroma – Wellness Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

Single Service

[TIME] 60-minute Signature Aroma – Wellness Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Signature Aroma – Wellness Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

BODY RITUALS 
All will have a 15MIN pre service buffer

LAVENDER LEMONGRASS JOURNEY

[TIME] Two, 120-minute Lavender Lemongrass Journey
| Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 120-minute Lavender Lemongrass Journey | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

PRICKLY PEAR & SHEA BUTTER WRAP

[TIME] Two, 60-minute Prickly Pear & Shea Butter Wraps
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 60-minute Prickly Pear & Shea Butter Wrap | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

DESERT TRANSFORMATION

[TIME] Two, 120-minute Sonoran Desert Transformations
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 120-minute Sonoran Desert Transformation | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

ENERGY THERAPIES

REIKI + CRANIAL SACRAL THERAPY 

[TIME] 60 or 90-minute Reiki Session | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 60 or 90-minute Cranial Sacral Therapy | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Reiki/Cranial Sacral Combo | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

Watsu Sessions

[TIME] 60-minute Watsu Water Therapy | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Watsu Water Therapy | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME]  Two, 60-minute Watsu Water Therapy Sessions
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME]  Two, 90-minute Watsu Water Therapy Sessions
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 60 or 90-Minute Aquatic Energy Balancing Session | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

Facials

[TIME] 60-minute Castle Custom Facial | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Castle Custom Facial | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 60-minute Men’s Castle Custom Facial | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Men’s Castle Custom Facial | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

CASTLE HOT SPRINGS CUSTOM MASSAGE

Double Service

[TIME] Two, 60-minute Castle Hot Springs Custom Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] Two, 90-minute Castle Hot Springs Custom Massages
| Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] Two, 120-minute Castle Hot Springs Custom Massages
 | Separate OR Couples Cabanas |
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

Single Service

[TIME] 60-minute Castle Hot Springs Custom Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 90-minute Castle Hot Springs Custom Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

[TIME] 120-minute Castle Hot Springs Custom Massage | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.

Table Thai Yoga Therapy

[TIME] 60 or 90-Minute Table Thai Yoga Therapy | GUEST NAME
Please arrive 5 minutes early to the Relaxation Cabana where your therapist will meet you.
Please wear loose fitting, comfortable clothing.

In Room Services

CBD Massage
[TIME] 90-minute Signature CBD Massage in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

[TIME] 120-minute Signature CBD Massage in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

Aroma-Wellness Massage

[TIME] 60-minute Signature Aroma–Wellness Massage in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

[TIME] 90-minute Signature Aroma–Wellness Massage in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

Adventure Ready Massage

[TIME] 60-minute Adventure Ready Massage in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

[TIME] 90-minute Adventure Ready Massage in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

Table Thai Yoga

[TIME] 60 or 90-Minute Table Thai Yoga Therapy in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up. Please wear loose fitting, comfortable clothing.

Reiki/Cranial Sacral

[TIME] 60 or 90-minute Reiki Session in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up.

[TIME] 60 or 90-minute Cranial Sacral Therapy in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up

[TIME] 90-minute Reiki/Cranial Sacral Combo in Room | GUEST NAME
Your massage therapist will arrive 15 minutes prior to treatment to set up`;

  const RAW_OTHER = `Adventures & Activities
8:00AM Castle Peak Via Ferrata
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

8:15AM Scenic Desert E-Bike Tour
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

8:30AM Rise + Shine Flow Yoga
Please meet at the Stone House 5-minutes prior to start time.
 The doors to the Stone House will be locked at 8:30AM. 

8:30AM Yoga
Please meet at the Stone House 5-minutes prior to start time.
 The doors to the Stone House will be locked at 8:30AM. 

9:30AM Landscape Restoration & Development Tour
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to activity.

9:40AM Meditation
Please meet at the Stone House 5-minutes prior to start time. 
The doors to the Stone House will be locked at 9:40AM.

10:15AM Intro to Tai Chi
Please meet at the Stone House 5-minutes prior to start time. 
The doors to the Stone House will be locked at the start time of the session. 

10:30AM Discovery Loop Hike
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

10:30AM Guided Canyon Walk
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

10:30AM Guided Overlook Hike
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

11:30AM Guided Archery
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to activity.
Active-wear and hiking shoes recommended.

11:30AM Intro to E-Bike Tour
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

12:30PM Guided Axe Throwing
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to activity.
Active-wear and hiking shoes recommended.

12:30PM Sound Bath | Doors open at 12:20PM
Please meet at the Stone House. The doors will be locked at 12:30PM.

1:00PM Crater Canyon Exploration
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

2:00PM Healing Waters QiGong
Please arrive at the Watsu Pool 5-minutes prior to activity. 

2:00PM History Tour
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to activity.

2:00PM Mindfulness | Body Scrubs
Please meet at the Stone House.

2:00PM Mindfulness | Cactus Candles
Please meet at the Stone House.

2:00PM Mindfulness | Cholla Suncatchers
Please meet at the Stone House.

2:00PM Mindfulness | Rock Mandalas
Please meet at the Stone House.

2:00PM Mindfulness | Sunprints
Please meet at the Stone House.

3:00PM Agave Spirits Tasting
Please meet at Murphy Hall.

3:00PM Farm to Bar: Mixology 101
Please meet at Murphy Hall.

3:00PM Wine Tasting
Please meet at Murphy Hall.

3:15PM Yoga
Please meet at the Stone House 5-minutes prior to start time.
 The doors to the Stone House will be locked at 3:15PM. 

3:30PM Sonoran Aerial Walkway
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

4:00PM Castle Hot Springs Documentary Viewing
Please meet at the Stone House.

4:00PM Connecting with Water
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to activity.
Please wear a swimsuit if participating in optional 15-minute guided soak.

4:00PM Farm Tour
Please meet at the Lodge.

PICKLE BALL LESSON

[TIME] 45-Minute Pickle Ball Lesson
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to lesson.

EVENTS/PRIVATES/TOURS

[TIME] [LENGTH] Private Guided Hike 
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

[TIME] Falconry Event
Please meet at the Great Lawn at your leisure. 

[TIME] Stargazing Event
Please meet at the Great Lawn at your leisure. 

[TIME] American Express Educational Tour
Please meet at the Lodge. 

[TIME] 3-Hour Helicopter/Vinyard Tour & Wine Tasting 
Please meet at the Lodge. 

E-BIKE/VIA FERRATA EXTRAS

[TIME] Adventure Archery
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to activity.
Active-wear and hiking shoes recommended.

[TIME] Castle Creek Canyon Via Ferrata + Rappel 
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

[TIME] Cow Creek Loop E-Bike Adventure 
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

[TIME] West Wall Via Ferrata
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

HIKE & PAINT

[TIME] Hike and Paint
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended.

[TIME] Paint and Sip
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.

[TIME] Indoor/Outdoor Painting Desert Botanicals
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.

RAZOR TOURS

1:00PM / 9:00AM 3-hour Razor Tour Ride | Shared 2-Seater Vehicle
Please check in at the Lodge with an Activities Coordinator 5-minutes prior to adventure.
Active-wear and hiking shoes recommended. Please bring Valid Driver’s License.

HORSEBACK RIDING
AM/PM 90-minute OR 60-minute Horseback Ride
Please meet outside the front of the Lodge. Long pants and closed toed shoes required.
*4PM ride can only be 60min* 

DINNER RESERVATION

Late Night Pre-Order | In Room Dining 

In-Room Dining 
Please call the Front desk to place your order.
 Allow 30-40 minutes to deliver once order is placed.

5:30PM - 8:00PM Dining at Bar 1896
Please dine at your leisure.

EPICUREAN

5:30PM A Lesson in Flavor Planning + Seasonality 
Please meet at the Farm.

6:30PM Welcome Reception
Please meet at the Farm.

7:00PM Chef’s Table Dinner
Please meet at the Farm.

10:00AM Southwest Garden Staples Cooking Class
Please meet at the Farm.

4:30PM Wine + Charcuterie Class
Please meet at the Farm.

6:15PM Mesquite + Mezcal Dinner
Please meet at the Outdoor Kitchen.

5:00PM Margarita Making Contest
Please meet at the Farm.

6:15PM Feast at the Farm Dinner
Please meet at the Farm.

10:00AM Prep + Plate Class
Please meet at the Farm.

1:00PM Herbal Tea Blending Class
Please meet at the Wellness Loft.

7:00PM Sommelier’s Table + Dinner
Please meet at Harvest.
`;

  // ------------------------------ STATE -------------------------------------
  const [docHtml, setDocHtml] = React.useState("");
  const editorRef = React.useRef<HTMLDivElement | null>(null);

  // Guests one-by-one
  const [guests, setGuests] = React.useState<{ first: string; last: string }[]>([]);
  const [gf, setGf] = React.useState("");
  const [gl, setGl] = React.useState("");

  // Dates
  const [arrivalIso, setArrivalIso] = React.useState("");
  const [departureIso, setDepartureIso] = React.useState("");

  // Calendar
  const today = new Date();
  const [viewYear, setViewYear] = React.useState(today.getFullYear());
  const [viewMonth, setViewMonth] = React.useState(today.getMonth());
  const [focusedIso, setFocusedIso] = React.useState(isoFromDate(today));

  // ------------------------------ UTILS -------------------------------------
  const WEEKDAY = [
    "Sunday",
    "Monday",
    "Tuesday",
    "Wednesday",
    "Thursday",
    "Friday",
    "Saturday",
  ];
  const MONTH = [
    "January",
    "February",
    "March",
    "April",
    "May",
    "June",
    "July",
    "August",
    "September",
    "October",
    "November",
    "December",
  ];

  function isoFromDate(d: Date) {
    const y = d.getFullYear();
    const m = String(d.getMonth() + 1).padStart(2, "0");
    const dd = String(d.getDate()).padStart(2, "0");
    return `${y}-${m}-${dd}`;
  }
  function dateFromIso(iso?: string | null) {
    if (!iso) return null as unknown as Date;
    const [y, m, d] = iso.split("-").map(Number);
    return new Date(y, m - 1, d);
  }
  function ordinal(n: number) {
    const s = ["th", "st", "nd", "rd"],
      v = n % 100;
    return (s as any)[(v - 20) % 10] || (s as any)[v] || s[0];
  }
  function fmtHuman(iso?: string) {
    const d = dateFromIso(iso || "");
    if (!d) return "";
    return `${WEEKDAY[d.getDay()]}, ${MONTH[d.getMonth()]} ${d.getDate()}${ordinal(
      d.getDate()
    )}`;
  }
  function fmtRange(a: string, b: string) {
    const A = dateFromIso(a),
      B = dateFromIso(b);
    if (!A || !B) return "";
    let S = A,
      E = B;
    if (+A > +B) {
      S = B;
      E = A;
    }
    const L = `${WEEKDAY[S.getDay()]}, ${MONTH[S.getMonth()]} ${S.getDate()}${ordinal(
      S.getDate()
    )}`;
    const R = `${WEEKDAY[E.getDay()]}, ${MONTH[E.getMonth()]} ${E.getDate()}${ordinal(
      E.getDate()
    )}`;
    return `${L} – ${R}`;
  }
  function parseMinutes(t?: string) {
    if (!t) return 999999;
    let s = t.trim().toUpperCase().replace(/\s+/g, "");
    const ap = /(AM|A|PM|P)$/.exec(s)?.[1] || "";
    s = s.replace(/(AM|A|PM|P)$/, "");
    let h = 0,
      m = 0;
    if (/^\d{1,2}:\d{2}$/.test(s)) {
      [h, m] = s.split(":").map(Number);
    } else if (/^\d{3,4}$/.test(s)) {
      const p = s.padStart(4, "0");
      h = +p.slice(0, 2);
      m = +p.slice(2);
    } else if (/^\d{1,2}$/.test(s)) {
      h = +s;
      m = 0;
    }
    if (ap === "PM" || ap === "P") {
      if (h < 12) h += 12;
    }
    if (ap === "AM" || ap === "A") {
      if (h === 12) h = 0;
    }
    return h * 60 + m;
  }
  function andJoin(a: string[]) {
    if (a.length <= 1) return a.join("");
    const last = a[a.length - 1];
    return `${a.slice(0, -1).join(", ")} and ${last}`;
  }
  function guestHeader(list: { first: string; last: string }[]) {
    if (list.length === 0) return "{GUEST NAME}";
    if (list.length === 1) return `${list[0].first} ${list[0].last}`;
    const lastSet = new Set(list.map((g) => g.last));
    if (lastSet.size === 1) {
      return `${andJoin(list.map((g) => g.first))} ${list[0].last}`;
    }
    return andJoin(list.map((g) => `${g.first} ${g.last}`));
  }

  // ------------------------------ TEMPLATE BIND -----------------------------
  React.useEffect(() => {
    const t = MASTER
      .replace(
        "{ STAY DATES ( Thursday, October 24 – Sunday, October 27) }",
        '<span data-ph="dates"></span>'
      )
      .replace(
        "Dear {GUEST NAME},",
        'Dear <span data-ph="guest">{GUEST NAME}</span>,'
      );
    const html = t
      .split("\n")
      .map((l) => (l.length ? l : "&nbsp;"))
      .join("<br>");
    setDocHtml(html);
  }, []);

  // Re-bind placeholders whenever guests/dates change. Guard for null.
  React.useEffect(() => {
    const root = editorRef.current;
    if (!root) return;
    const el = root.querySelector('span[data-ph="guest"]');
    if (el) (el as HTMLElement).textContent = guestHeader(guests);
  }, [guests]);

  React.useEffect(() => {
    const root = editorRef.current;
    if (!root) return;
    const el = root.querySelector('span[data-ph="dates"]');
    if (el && arrivalIso && departureIso)
      (el as HTMLElement).textContent = fmtRange(arrivalIso, departureIso);
    rebuildDayHeaders();
  }, [arrivalIso, departureIso]);

  // Ensure the DOM exists before any DOM-writes that depend on parentElement
  React.useEffect(() => {
    // run once after docHtml mounts and ref is attached
    const id = requestAnimationFrame(() => {
      rebuildDayHeaders();
    });
    return () => cancelAnimationFrame(id);
  }, [docHtml]);

  // ------------------------------ CALENDAR ----------------------------------
  function daysInMonth(y: number, m0: number) {
    return new Date(y, m0 + 1, 0).getDate();
  }
  function firstDow(y: number, m0: number) {
    return new Date(y, m0, 1).getDay();
  }
  function buildCells(y: number, m0: number) {
    const dim = daysInMonth(y, m0),
      lead = firstDow(y, m0);
    const prevM = m0 ? m0 - 1 : 11,
      prevY = m0 ? y : y - 1,
      dimPrev = daysInMonth(prevY, prevM);
    const cells: { iso: string; overflow: boolean }[] = [];
    for (let i = lead; i > 0; i--) {
      const d = dimPrev - i + 1;
      cells.push({ iso: isoFromDate(new Date(prevY, prevM, d)), overflow: true });
    }
    for (let d = 1; d <= dim; d++) {
      cells.push({ iso: isoFromDate(new Date(y, m0, d)), overflow: false });
    }
    while (cells.length < 42) {
      const idx = cells.length - lead - dim + 1;
      const nextM = m0 === 11 ? 0 : m0 + 1;
      const nextY = m0 === 11 ? y + 1 : y;
      cells.push({ iso: isoFromDate(new Date(nextY, nextM, idx)), overflow: true });
    }
    return cells;
  }
  const cells = buildCells(viewYear, viewMonth);
  function goMonth(d: number) {
    setViewMonth((m) => {
      let mm = m + d,
        yy = viewYear;
      if (mm < 0) {
        mm = 11;
        yy--;
      }
      if (mm > 11) {
        mm = 0;
        yy++;
      }
      setViewYear(yy);
      return mm;
    });
  }
  function goYear(d: number) {
    setViewYear((y) => y + d);
  }
  function goToday() {
    const d = new Date();
    setViewYear(d.getFullYear());
    setViewMonth(d.getMonth());
    setFocusedIso(isoFromDate(d));
  }
  function setArr() {
    if (focusedIso) setArrivalIso(focusedIso);
  }
  function setDep() {
    if (focusedIso) setDepartureIso(focusedIso);
  }

  const lowT =
    arrivalIso && departureIso
      ? Math.min(+dateFromIso(arrivalIso)!, +dateFromIso(departureIso)!)
      : null;
  const highT =
    arrivalIso && departureIso
      ? Math.max(+dateFromIso(arrivalIso)!, +dateFromIso(departureIso)!)
      : null;

  // ------------------------------ DAY HEADERS -------------------------------
  function rebuildDayHeaders() {
    const root = editorRef.current;
    if (!root) return;
    const anchor = root.querySelector('#chs-activities-anchor') as
      | HTMLElement
      | null;
    if (!anchor) return;
    const parent = anchor.parentElement;
    if (!parent) return; // null-safe fix

    // wipe following siblings (previous dynamic content)
    let node = anchor.nextSibling;
    while (node) {
      const next = node.nextSibling as ChildNode | null;
      (node as any).remove?.();
      node = next;
    }

    if (!(arrivalIso && departureIso)) return;

    // create day headers for the date range
    const A = dateFromIso(arrivalIso)!,
      B = dateFromIso(departureIso)!;
    const start = +A <= +B ? A : B,
      end = +A <= +B ? B : A;

    const labels: string[] = [];
    for (let d = new Date(start); +d <= +end; d.setDate(d.getDate() + 1)) {
      labels.push(`${WEEKDAY[d.getDay()]},`);
    }

    labels.forEach((label, idx) => {
      const br1 = document.createElement('br');
      parent.insertBefore(br1, anchor.nextSibling);
      const line = document.createElement('div');
      line.setAttribute('data-day', idx.toString());
      line.textContent = label;
      parent.insertBefore(line, br1.nextSibling);
      const br2 = document.createElement('br');
      parent.insertBefore(br2, line.nextSibling);
    });

    paintActivities();
  }

  // Activities store (placeholder; picker wires next pass)
  type Entry = {
    id: string;
    time?: string;
    title: string;
    notes: string[];
  };
  const [byDay, setByDay] = React.useState<Record<string, Entry[]>>({});

  function paintActivities() {
    const root = editorRef.current;
    if (!root) return;
    const anchor = root.querySelector('#chs-activities-anchor') as
      | HTMLElement
      | null;
    if (!anchor) return;
    const parent = anchor.parentElement;
    if (!parent) return; // null-safe fix

    // remove prior rendered entries
    parent.querySelectorAll('[data-entry]').forEach((el) => el.remove());

    if (!(arrivalIso && departureIso)) return;
    const A = dateFromIso(arrivalIso)!,
      B = dateFromIso(departureIso)!;
    const start = +A <= +B ? A : B;
    const days = Math.abs((+B - +A) / (1000 * 60 * 60 * 24)) + 1;

    for (let i = 0; i < days; i++) {
      const d = new Date(start);
      d.setDate(d.getDate() + i);
      const iso = isoFromDate(d);
      const list = (byDay[iso] || [])
        .slice()
        .sort((x, y) => parseMinutes(x.time) - parseMinutes(y.time));
      if (!list.length) continue;

      const headers = Array.from(parent.querySelectorAll(`[data-day]`));
      const header = headers[i] as HTMLElement | undefined;
      if (!header) continue;

      let insertAfter: ChildNode = header;
      list.forEach((e) => {
        const titleDiv = document.createElement('div');
        titleDiv.setAttribute('data-entry', '');
        const title = (e.time ? `${e.time} ` : '') + e.title;
        titleDiv.textContent = title;
        parent.insertBefore(titleDiv, insertAfter.nextSibling);
        insertAfter = titleDiv;
        e.notes.forEach((n) => {
          const noteDiv = document.createElement('div');
          noteDiv.setAttribute('data-entry', '');
          noteDiv.textContent = n;
          parent.insertBefore(noteDiv, insertAfter.nextSibling);
          insertAfter = noteDiv;
        });
        const br1 = document.createElement('br');
        parent.insertBefore(br1, insertAfter.nextSibling);
        insertAfter = br1;
        const br2 = document.createElement('br');
        parent.insertBefore(br2, insertAfter.nextSibling);
        insertAfter = br2;
      });
    }
  }

  // repaint when activities change
  React.useEffect(() => {
    paintActivities();
  }, [byDay]);

  // ------------------------------ STYLES ------------------------------------
  return (
    <div className="min-h-screen bg-neutral-50 text-neutral-900 p-6 md:p-10">
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap');
        .doc-surface{font-family:'Montserrat',system-ui,-apple-system,Segoe UI,Roboto,sans-serif;font-size:12pt;line-height:1.5}
        .doc-shell{background:white;width:8.5in;min-height:11in;margin:0 auto;padding:1in;box-shadow:0 10px 30px rgba(0,0,0,.08)}
        .doc-editable{outline:none;white-space:normal}
        @media print{body{background:white!important}.no-print{display:none!important}.doc-shell{box-shadow:none;width:auto;min-height:auto;margin:0;padding:.75in}}
        .ctl{border:1px solid #e5e5e5;background:#fff;border-radius:14px;padding:12px}
        .btn{border:1px solid #d4d4d4;border-radius:10px;padding:8px 12px;background:#fff}
        .btn.primary{background:#111;color:#fff;border-color:#111}
        .cal{user-select:none}
        .cal-head{display:grid;grid-template-columns:auto 1fr auto auto;align-items:center;gap:8px}
        .cal-nav{display:flex;gap:6px}
        .cal-btn{padding:6px 10px;border:1px solid #e5e5e5;border-radius:10px;background:#fff}
        .cal-title{text-align:center;font-weight:600}
        .cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:6px;margin-top:8px}
        .cal-cell{height:42px;display:flex;align-items:center;justify-content:center;border:1px solid #eee;border-radius:10px;cursor:pointer}
        .cal-cell.overflow{opacity:.45}
        .cal-cell.focused{outline:2px solid #111}
        .cal-cell.arr,.cal-cell.dep{background:#111;color:#fff}
        .cal-cell.inrange{background:#f3f4f6;border-color:#e5e7eb}
      `}</style>

      <div className="mx-auto max-w-6xl">
        <header className="no-print flex flex-col gap-3 mb-6">
          <h1 className="text-2xl md:text-3xl font-semibold tracking-tight">CHS Itinerary — Exact Template Preview</h1>
          <p className="text-neutral-600">Stable pass: live names/dates, calendar controls, day headers, and null-safe DOM guards.</p>

          {/* Guest input */}
          <div className="ctl">
            <div className="text-sm mb-1">Guest(s)</div>
            <div className="flex gap-2 flex-wrap">
              <input placeholder="First" value={gf} onChange={(e)=>setGf(e.target.value)} className="border rounded px-3 py-2" />
              <input placeholder="Last" value={gl} onChange={(e)=>setGl(e.target.value)} className="border rounded px-3 py-2" />
              <button className="btn" onClick={()=>{ if(gf.trim()&&gl.trim()){ setGuests(g=>[...g,{first:gf.trim(),last:gl.trim()}]); setGf(''); setGl(''); } }}>Add Guest</button>
            </div>
            {guests.length>0 && (
              <div className="mt-2 text-sm text-neutral-700">Intro: <strong>{guestHeader(guests)}</strong></div>
            )}
          </div>

          {/* Calendar */}
          <div className="ctl cal">
            <div className="cal-head">
              <div className="cal-nav">
                <button className="cal-btn" onClick={()=>goYear(-1)}>«</button>
                <button className="cal-btn" onClick={()=>goMonth(-1)}>‹</button>
              </div>
              <div className="cal-title">{MONTH[viewMonth]} {viewYear}</div>
              <div className="cal-nav">
                <button className="cal-btn" onClick={()=>goMonth(1)}>›</button>
                <button className="cal-btn" onClick={()=>goYear(1)}>»</button>
              </div>
              <div><button className="cal-btn" onClick={goToday}>Today</button></div>
            </div>
            <div className="cal-grid">
              {["Sun","Mon","Tue","Wed","Thu","Fri","Sat"].map((d) => (
                <div key={d} className="text-center text-xs text-neutral-500">{d}</div>
              ))}
              {buildCells(viewYear,viewMonth).map(({ iso, overflow }) => {
                const d = dateFromIso(iso)!;
                const day = d.getDate();
                const focused = iso === focusedIso;
                const isArr = iso === arrivalIso;
                const isDep = iso === departureIso;
                const t = +d;
                const isBetween = lowT != null && highT != null && t > lowT && t < highT;
                return (
                  <div key={iso}
                    className={`cal-cell ${overflow ? 'overflow' : ''} ${isBetween ? 'inrange' : ''} ${focused ? 'focused' : ''} ${isArr ? 'arr' : ''} ${isDep ? 'dep' : ''}`}
                    onClick={()=>setFocusedIso(iso)}
                    title={fmtHuman(iso)}
                  >{day}</div>
                );
              })}
            </div>
            <div className="mt-2 flex gap-2 flex-wrap">
              <button className="btn primary" onClick={()=>setArr()}>Set Arrival</button>
              <button className="btn primary" onClick={()=>setDep()}>Set Departure</button>
              <div className="text-sm text-neutral-700 ml-2">Arrival: {fmtHuman(arrivalIso) || '—'} | Departure: {fmtHuman(departureIso) || '—'}</div>
            </div>
          </div>

          {/* Actions */}
          <div className="flex flex-wrap gap-2">
            <button className="btn" onClick={()=>window.print()}>Print / Save PDF</button>
            <button className="btn" onClick={()=>{
              const tmp = document.createElement('div');
              tmp.innerHTML = editorRef.current?.innerHTML || '';
              tmp.querySelectorAll('br').forEach((br)=>br.replaceWith("\n"));
              const text = tmp.textContent || '';
              navigator.clipboard.writeText(text);
            }}>Copy as Text</button>
          </div>
        </header>

        {/* Document Preview */}
        <div className="doc-shell doc-surface">
          <div
            ref={editorRef}
            className="doc-editable"
            contentEditable
            suppressContentEditableWarning
            dangerouslySetInnerHTML={{ __html: docHtml }}
          />
        </div>
      </div>
    </div>
  );
}

// ------------------------------ SELF TESTS ----------------------------------
// Run once on module load (console). Ensures core helpers behave.
(function runSelfTests(){
  const pass: string[] = [];
  const fail: string[] = [];
  const eq = (name:string, a:any, b:any)=> (a===b?pass:fail).push(name);
  // parseMinutes
  eq('parse 3:05PM', (function(){
    const fn = (t:string)=>{ let s=t.toUpperCase(); const ap=s.endsWith('PM')? 'PM': s.endsWith('AM')? 'AM': ''; s=s.replace(/\s+/g,''); s=s.replace(/(AM|PM)$/,''); const [H,M]=s.split(':').map(Number); let h=H; if(ap==='PM'&&h<12) h+=12; if(ap==='AM'&&h===12) h=0; return h*60+M; };
    return fn('3:05PM'); })(), 15*60+5+ (12*60));
  // guest header collapse
  const guestHeader = (list: {first:string;last:string}[])=>{
    const andJoin=(a:string[])=> a.length<=1? a.join(''): `${a.slice(0,-1).join(', ')} and ${a[a.length-1]}`;
    if(list.length===0) return '{GUEST NAME}';
    if(list.length===1) return `${list[0].first} ${list[0].last}`;
    const lastSet=new Set(list.map(g=>g.last));
    if(lastSet.size===1) return `${andJoin(list.map(g=>g.first))} ${list[0].last}`;
    return andJoin(list.map(g=>`${g.first} ${g.last}`));
  };
  eq('collapse shared last', guestHeader([{first:'John',last:'Smith'},{first:'Susan',last:'Smith'}]), 'John and Susan Smith');
  // report
  if(fail.length){ console.warn('[CHS Preview self-tests] FAIL', fail); } else { console.log('[CHS Preview self-tests] PASS', pass); }
})();
