# Mobile Device Programming · Group assignment

Android app developed by our team for *Mobile Device Programming* (MDP), a course in the
[Master in Internet of Things (MIoT)](https://www.etsist.upm.es/estudios-ingenieria-sistemas-telecomunicaciones-madrid/masters-ingenieria-madrid/Master-IoT)
at Universidad Politécnica de Madrid.

## The project: active mobility guided by air quality

An app that encourages people to walk instead of driving, and tells them when and where the air is
cleanest to do it.

- **Air quality:** reads the City of Madrid open data on air quality and its monitoring stations, with their coordinates, to show the conditions near you.
- **Walking tracker:** the phone's step counter or accelerometer measures the distance you walk and the CO₂ you avoid compared with a car trip.
- **Friends and ranking:** each phone publishes its trip summary over MQTT as a retained message and subscribes to everyone else's. This builds a group leaderboard and lets you follow your friends.
- **Accessible by design:** large text, high contrast and simple navigation, with older adults in mind.

| Repository | Status |
|---|---|
| `mdp2627-active-mobility` | In development. Private until the delivery at the end of November 2026. |

## Stack

- **Language and UI:** Kotlin, Jetpack Compose, Material 3
- **Architecture:** ViewModel and UI state
- **Data:** Madrid open data (REST/JSON), MQTT
- **Sensors:** step counter, accelerometer and location
- **Reference device:** Motorola Moto G35

## Team

| | |
|---|---|
| Carlos Egea | [@cegea](https://github.com/cegea) |
| Omar Piñeiro | [@Omarpparada](https://github.com/Omarpparada) |
| Pablo Hernández | [@PabloHernaez](https://github.com/PabloHernaez) |
