[content.json](https://github.com/user-attachments/files/26999324/content.json)
# shipmind-content
Structured knowledge base for the ShipMind app — offline-first content for seafarers.
{
  "version": 1,
  "last_updated": "2026-04-23",
  "topics": [
    {
      "id": "ecdis",
      "title": "ECDIS",
      "category": "Navigation",
      "what_is_it": "ECDIS stands for Electronic Chart Display and Information System. It's the digital chart table that replaced paper charts on most commercial vessels since 2012. Think of it as Google Maps for ships — but with legal consequences if you get it wrong.",
      "why_it_exists": "Ships used to navigate using paper charts, which had to be updated manually with corrections every week. ECDIS replaced that with real-time digital charts that integrate GPS, AIS, and radar — giving officers a live picture of the ship's position at all times.",
      "how_it_works": "ECDIS pulls your GPS position and overlays it on an electronic navigational chart (ENC). It continuously monitors your route, depth under keel, and nearby hazards. If you're heading toward shallow water or a traffic separation zone, it sounds an alarm.",
      "common_confusion": "Most junior officers panic when alarms start going off and they don't know which setting triggered it. ECDIS has dozens of alarm parameters — safety contour, anti-grounding cone, cross-track error — and each brand (Furuno, JRC, Transas) has a different interface.",
      "quick_tips": "1. Learn your ship's specific ECDIS brand during familiarization — don't assume it works like the simulator. 2. Never silence an alarm you don't understand. 3. Always cross-check ECDIS position with radar and visual bearings. 4. Make sure ENCs are up to date before departure."
    },
    {
      "id": "gmdss",
      "title": "GMDSS",
      "category": "Communication",
      "what_is_it": "GMDSS stands for Global Maritime Distress and Safety System. It's the worldwide communication network that ensures a ship in distress can always send and receive emergency signals — no matter where in the ocean they are.",
      "why_it_exists": "Before GMDSS, distress communication depended on a radio operator being awake and on duty. Ships have sunk because no one heard the SOS in time. GMDSS automates distress alerting so that a single button press notifies rescue services and nearby ships simultaneously.",
      "how_it_works": "GMDSS uses a combination of equipment depending on the sea area (A1, A2, A3, A4). This includes DSC (Digital Selective Calling) on VHF/MF/HF radios, EPIRB (Emergency Position Indicating Radio Beacon), SART (Search and Rescue Transponder), Inmarsat satellite terminals, and NAVTEX for automated safety broadcasts.",
      "common_confusion": "People mix up the equipment and which sea area requires what. Also, the DSC controller on VHF radio is often ignored during normal operations — then in an emergency nobody knows how to send a distress alert properly.",
      "quick_tips": "1. Know where every piece of GMDSS equipment is on your ship before you need it. 2. The red distress button on VHF DSC is covered for a reason — lift the cover, hold for 5 seconds. 3. EPIRB should be checked monthly — look at the indicator light and hydrostatic release condition. 4. NAVTEX runs automatically — check it daily for weather and navigational warnings in your area."
    },
    {
      "id": "ais",
      "title": "AIS",
      "category": "Navigation",
      "what_is_it": "AIS stands for Automatic Identification System. It's a transponder system that broadcasts your ship's identity, position, speed, and course to every other vessel and shore station within range — and receives the same data from them.",
      "why_it_exists": "Radar can see a target but can't tell you who it is, where it's going, or how fast. AIS fills that gap. It was introduced to reduce collisions, especially in busy traffic lanes, ports, and restricted visibility.",
      "how_it_works": "Your AIS unit continuously transmits a VHF signal containing your MMSI number, ship name, position, COG, SOG, heading, and destination. Other ships receive this and display it as a labelled target on ECDIS or a dedicated AIS display. Class A AIS (required on SOLAS vessels) updates every 2–10 seconds when underway.",
      "common_confusion": "AIS is not a collision avoidance system. It's an information tool. Junior officers sometimes trust AIS targets over radar — this is dangerous. AIS can be switched off, misconfigured, or broadcasting wrong data. Always use radar as your primary collision avoidance tool.",
      "quick_tips": "1. Check your own AIS data regularly — wrong ship length or draught input causes confusion for other vessels. 2. If a target disappears from AIS but is still on radar, don't assume it's safe — they may have switched AIS off. 3. In port, AIS helps you identify anchored vessels in the dark. 4. MMSI is your ship's unique ID — know it."
    },
    {
      "id": "ballast-water-treatment",
      "title": "Ballast Water Treatment",
      "category": "Engine Room",
      "what_is_it": "Ballast Water Treatment (BWT) systems clean the water taken into a ship's ballast tanks before it's discharged in a different ocean. The goal is to stop invasive marine species from hitchhiking between ecosystems inside ballast water.",
      "why_it_exists": "Ships take in millions of litres of seawater as ballast to maintain stability when carrying no cargo. That water contains plankton, larvae, and bacteria from the local sea. When discharged at the destination port, these organisms can devastate local marine environments. The IMO's Ballast Water Management Convention made treatment systems mandatory.",
      "how_it_works": "Most systems use two stages: filtration (removing large organisms and sediment) followed by either UV irradiation or electrochlorination (killing remaining microorganisms). The treated water must meet D-2 standards — essentially near-zero live organisms of a certain size per cubic metre.",
      "common_confusion": "Ratings often don't know when the system should be running or how to log its operation correctly. Port State Control inspectors check ballast water records closely — incorrect or missing log entries can get a ship detained even if the system worked perfectly.",
      "quick_tips": "1. Always record ballast operations in the Ballast Water Record Book — time, position, volume, system status. 2. Check filter differential pressure regularly — a clogged filter means the UV stage isn't getting clean water. 3. UV lamp hours matter — know when your lamps are due for replacement. 4. Some ports have additional local requirements beyond IMO D-2 — check before arrival."
    },
    {
      "id": "integrated-bridge-system",
      "title": "Integrated Bridge System",
      "category": "Navigation",
      "what_is_it": "An Integrated Bridge System (IBS) connects all navigation and ship control equipment — ECDIS, radar, autopilot, engine controls, AIS, GMDSS — into a single unified workstation. Instead of separate screens and panels, the officer works from one or two consoles that show everything.",
      "why_it_exists": "Modern ships generate enormous amounts of data from dozens of systems. Without integration, an officer would have to physically walk between different panels to get a complete picture. IBS brings it all together, reduces workload, and cuts human error — especially during critical manoeuvres like port entry.",
      "how_it_works": "All systems are networked through a central processing unit. The officer can pull radar overlay onto the ECDIS chart, receive engine RPM feedback directly on the nav console, and initiate autopilot course changes from the same screen. Alarms from any connected system surface centrally so nothing gets missed.",
      "common_confusion": "Because everything looks connected, junior officers sometimes assume that changing a setting in one system automatically updates the others. It doesn't always. ECDIS and radar may share position data but have independent alarm settings. Always configure each system individually during familiarization.",
      "quick_tips": "1. During familiarization, trace the data flow — know what feeds what on your specific IBS brand. 2. If one system fails, understand which other systems lose data as a result. 3. IBS doesn't replace watchkeeping judgment — it supports it. 4. Learn the manual fallback for every function in case the network goes down."
    }
  ]
}
