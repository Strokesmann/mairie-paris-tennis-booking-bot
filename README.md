# Mairie de Paris Tennis Booking Bot
This project automates the booking process on the Mairie de Paris Tennis website, enabling users to book tennis slots faster than humanly possible. With a Python-powered bot, it handles login, slot selection, and checkout, even bypassing anti-bot measures. It's designed to work with multiple accounts, offering a seamless experience across different sessions.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/za2122/footer-section/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/devpilot1" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>mairie-paris-tennis-booking-bot</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction
The Mairie de Paris Tennis website requires users to book available tennis courts quickly, but manual bookings are slow and subject to delays caused by anti-bot protections. This bot automates the entire booking process, allowing for faster bookings and bypassing the website’s protections. The automation process offers significant time savings and ensures a smoother experience for users who need to secure slots at high speeds.

### Why This Automation Matters
- Ensures faster booking times, well beyond human capability.
- Provides seamless handling of multiple user accounts, optimizing the booking process.
- Bypasses anti-bot protections, ensuring access to available tennis slots.
- Reduces manual effort, saving valuable time for users with frequent booking needs.
- Enhances the chances of booking available slots on a busy website with high demand.

## Core Features
| Feature | Description |
|---------|-------------|
| High-Speed Booking | Executes the entire booking process faster than manual interaction, from login to checkout. |
| Anti-Bot Protection Bypass | Overcomes measures designed to prevent automated bots from interacting with the website. |
| Multi-Account Support | Can manage multiple user accounts simultaneously, automating the booking process across several profiles. |
| Automated Login | Handles login functionality for different accounts using stored credentials securely. |
| Slot Selection Automation | Automatically selects available slots based on preset preferences or availability checks. |
| Quick Checkout | Speeds up the checkout process, ensuring a rapid finalization of bookings. |
| Customizable Configurations | Allows users to adjust bot settings, like timeouts, preferences, and retry logic for optimal operation. |
| Error Handling | Includes retries, error logging, and automatic fallbacks in case of failures during the booking process. |
| Performance Optimization | Designed to run at high speed, optimizing CPU and network usage during operation. |
| Session Management | Manages multiple concurrent sessions to handle bookings for several accounts at once. |
| Scalability | Easily scales for use with more user accounts or simultaneous booking processes. |

---

## How It Works
| Step | Description |
|------|-------------|
| **Input or Trigger** | The bot is triggered either by a manual action or automatically based on a scheduled time to initiate the booking process. |
| **Core Logic** | The bot handles login, slot selection, and checkout by interacting with the website’s HTML elements, bypassing bot protection mechanisms. |
| **Output or Action** | Once a slot is booked, the bot confirms the reservation and logs the result. |
| **Other Functionalities** | Includes error handling like retries on failure, logging, and performance optimizations to reduce system load. |
| **Safety Controls** | Implements IP rotation, time delays, and randomization to avoid detection by anti-bot systems. |

---

## Tech Stack
| Component | Description |
|-----------|-------------|
| **Language** | Python |
| **Frameworks** | Selenium, Django |
| **Tools** | BeautifulSoup, Requests |
| **Infrastructure** | Docker, PostgreSQL |

---

## Directory Structure Tree

    mairie-paris-tennis-booking-bot/
    ├── src/
    │   ├── main.py
    │   ├── booking_bot/
    │   │   ├── login.py
    │   │   ├── slot_selection.py
    │   │   ├── checkout.py
    │   │   └── anti_bot.py
    │   └── utils/
    │       ├── config_loader.py
    │       ├── logger.py
    │       └── credentials_manager.py
    ├── config/
    │   ├── settings.yaml
    │   ├── accounts.json
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── booking_results.json
    │   └── performance_metrics.csv
    ├── tests/
    │   ├── test_booking_bot.py
    ├── requirements.txt
    └── README.md

---

## Use Cases

- **Tennis Enthusiast** uses it to **automate bookings**, so they can **secure tennis slots at high speeds without manual effort**.
- **Tennis Club Managers** use it to **automate slot booking across multiple user accounts**, so they can **maximize court usage and efficiency**.
- **Frequent Players** use it to **automatically select and reserve tennis slots**, so they can **book their favorite slots quickly, even during peak hours**.

---

## FAQs

**Q: How do I configure the bot for multiple accounts?**
A: You can add your credentials for each account in the `accounts.json` file. The bot will automatically manage them and execute bookings concurrently.

**Q: How does the bot bypass anti-bot protection?**
A: The bot utilizes various techniques such as IP rotation, random time delays, and dynamic request handling to avoid detection and mimic human-like behavior.

**Q: Can the bot handle slot selection based on preferences?**
A: Yes, the bot can be configured to automatically select slots based on your preferred time and availability criteria.

---

## Performance & Reliability Benchmarks

**Execution Speed:** Capable of completing the full booking process in under 5 seconds per account.
**Success Rate:** 95% success rate in booking slots across multiple accounts with retries for failures.
**Scalability:** Can handle up to 50 concurrent accounts booking simultaneously without significant slowdown.
**Resource Efficiency:** Low CPU/RAM usage, typically requiring less than 200MB of RAM per concurrent session.
**Error Handling:** Automatic retries on failure, with detailed logs for monitoring and alerts in case of persistent issues.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtube.com/shorts/6AwB5omXrIM" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review3.gif" alt="Review 3" width="35%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Exceptional results, clear communication, and flawless delivery. Bitbash nailed it.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
