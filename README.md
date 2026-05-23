# Longitudinal Watch

An asynchronous time-series data pipeline and task-tracking engine that maps real-time, user-focused execution intervals directly onto an external calendar schema. Users can initialize target objectives, spin up active task trackers linked to specific project taxonomies, and view aggregate focused-work analytics while maintaining seamless state synchronization with the Google Calendar API.

## 🚀 System Architecture & Core Features
* **Asynchronous State Synchronization:** Implements live, bidirectional data pipelines between the client runtime environment and the Google Calendar API, ensuring task initialization registers immediately on external schedules.
* **Granular Time-Series Tracking:** Captures precision stopwatch intervals per task execution, aggregating multi-channel project data to compute exact duration metrics and focused-work analytics.
* **Dynamic Objective Provisioning:** Supports ad-hoc, daily target injections directly from the interface, automatically formatting and serializing payloads to match remote calendar event structures.
* **Low-Friction Deployment:** Architected for zero-configuration serverless environments, deploying instantly via Vercel integration.

## 🛠️ Technical Stack
* **Frontend/Engine:** HTML5, CSS3, JavaScript (Asynchronous Event Loop, Fetch API)
* **Integrations:** Google Calendar API (OAuth 2.0 / REST API integration)
* **Hosting/Deployment:** Vercel (Serverless Edge Framework)

## 📦 Architecture & Deployment Schema

### Prerequisites
To deploy this engine independently, you will need to provision access to the Google Calendar API through the Google Cloud Console.

### Local Initialization & Deployment
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/thenervez/longitudinal-watch.git](https://github.com/thenervez/longitudinal-watch.git)
   cd longitudinal-watch
