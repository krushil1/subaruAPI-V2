# subaruAPI-V2

New & improved functionality. Now supports starting Subaru with custom climate presets, shutting off the engine, lock, and unlock with FastAPI.

-Additional feature: Discord Webhook compatibility added to get faster notifications of Subaru Starlink service.

New routes for the application
  - **Lock**: <h6>HOSTING_URL/lock</h6>
  - **Unlock**: <h6>HOSTING_URL/unlock</h6>
  - **Start Engine**: <h6>HOSTING_URL/start/{climate_preset_name}</h6>
  - **Stop Engine**: <h6>HOSTING_URL/stop</h6>
