<div align="center">
<h1><kbd>🧩 FlightSeat</kbd></h1>
An extension for MIT App Inventor 2.<br>
Flight Seat Selection View - Developed by TechHamara using Fast.<br> <a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://buymeacoffee.com/techhamara/extras/' target='_blank'>BuyMeaCoffee</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.flightseat<br>
💾 **Size:** 32.76 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-11-17 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small><br>
**Library Used** Thank you **ldoublem** for your [FlightSeat](https://github.com/ldoublem/FlightSeat) library.<br>

## Demo

![Flight-demo-blocks.png](https://github.com/user-attachments/assets/1297926d-3d4e-4bd7-9afc-333e56b9e910)


![Flight1.gif](https://github.com/user-attachments/assets/3f8f42ee-7be9-424c-96db-3899d3b654b3)

![Flight2.gif](https://github.com/user-attachments/assets/958b4f79-82d6-43eb-9a2b-bf80f9136a65)

![Flight3.gif](https://github.com/user-attachments/assets/fa26f77a-a9eb-4863-9b06-dd41880ce1f2)


![IMG_20251119_151751_358.jpg](https://github.com/user-attachments/assets/c8c1ce6a-b6c6-424d-9051-7b452d37c937)

![flight_sheat.jpg](https://github.com/user-attachments/assets/855ec8c3-d4d2-4eb6-be03-dcba2766f53a)


## Blocks

<img width="253" height="85" alt="SeatTapped_Event" src="https://github.com/user-attachments/assets/8b3e2ddd-9e3a-4455-b4bb-bcca52df91ea" />
<img width="320" height="60" alt="MaxSelectionReached_Event" src="https://github.com/user-attachments/assets/8c56b885-16ee-4be5-a051-88cd6bf0dd72" />

-----

<img width="223" height="55" alt="Initialize_Method" src="https://github.com/user-attachments/assets/45465cb7-860e-481b-a859-7b33dc91b43b" />
<img width="292" height="26" alt="GetSelectingSeats_Method" src="https://github.com/user-attachments/assets/3664766a-b82e-4021-9231-76e6b6f034a0" />
<img width="289" height="26" alt="GetSelectedSeats_Method" src="https://github.com/user-attachments/assets/d20e70f8-8148-49aa-8906-4eff4dfae220" />
<img width="296" height="30" alt="ClearSelectingSeats_Method" src="https://github.com/user-attachments/assets/4422304f-07b3-4d4f-81ab-79ce6d0e89e1" />
<img width="293" height="30" alt="ClearSelectedSeats_Method" src="https://github.com/user-attachments/assets/b292e6a2-f11c-49cc-9e4d-33dcb63c4227" />
<img width="257" height="30" alt="StopAnimation_Method" src="https://github.com/user-attachments/assets/11d77879-8262-4868-b0f9-f485a7665e2d" />
<img width="258" height="30" alt="StartAnimation_Method" src="https://github.com/user-attachments/assets/badd5a3c-b960-4a9c-8e59-a98fc25829fb" />
<img width="257" height="80" alt="SeatSelected_Method" src="https://github.com/user-attachments/assets/8fe52cdf-16ad-4e01-b839-3c1c6d7cafb6" />
<img width="312" height="80" alt="RemoveSeatSelected_Method" src="https://github.com/user-attachments/assets/922b494d-32ff-46da-b5f6-1290d833953b" />

-----

<img width="335" height="30" alt="PlaneOutlineColor_Set_Property" src="https://github.com/user-attachments/assets/4e467ff5-8828-48a1-8d8c-a2f9564fa857" />
<img width="326" height="30" alt="PlaneCabinColor_Set_Property" src="https://github.com/user-attachments/assets/4bcb83ef-cc7e-4ab9-8625-693c5429a696" />
<img width="367" height="30" alt="PlaneBackgroundColor_Set_Property" src="https://github.com/user-attachments/assets/43fe5f8c-d24b-4339-a82e-c226bd320a22" />
<img width="325" height="30" alt="MaxSelectStates_Set_Property" src="https://github.com/user-attachments/assets/ebcbbb9c-a513-4767-9b6e-7a8b5e53e07a" />
<img width="265" height="26" alt="MaxSelectStates_Get_Property" src="https://github.com/user-attachments/assets/fc433c00-f9bd-47a2-a04b-fa35995ccde0" />
<img width="499" height="30" alt="GoToCabinPosition_Set_Property" src="https://github.com/user-attachments/assets/40d82d51-e62f-4faa-b4d8-bd457d9df34b" />
<img width="311" height="30" alt="PlaneTailColor_Set_Property" src="https://github.com/user-attachments/assets/98e28eee-c987-42fa-83d6-84318913cce5" />


## <kbd>Events:</kbd>
**FlightSeat** has total 2 events.

### SeatTapped
Event raised when a seat is tapped/selected by the user.

| Parameter | Type
| - | - |
| row | number
| column | number

### MaxSelectionReached
Event raised when the maximum selection limit is reached.

## <kbd>Methods:</kbd>
**FlightSeat** has total 9 methods.

### Initialize
Initialize the FlightSeat view inside an arrangement (HorizontalArrangement or VerticalArrangement).

| Parameter | Type
| - | - |
| arrangement | component

### StartAnimation
Start the zoom in animation to show the seat map.

### StopAnimation
Start the zoom out animation to hide the seat map.

### SeatSelected
Set a seat as selected at the given row and column (0-indexed).

| Parameter | Type
| - | - |
| row | number
| column | number

### RemoveSeatSelected
Remove a seat from selected at the given row and column (0-indexed).

| Parameter | Type
| - | - |
| row | number
| column | number

### ClearSelectedSeats
Clear all selected seats.

### ClearSelectingSeats
Clear all selecting (temporarily selected) seats.

### GetSelectedSeats
Get the list of selected seats as a list of strings in format 'row#column'.

* Return type: `list`

### GetSelectingSeats
Get the list of currently selecting (temporarily selected) seats as a list of strings in format 'row#column'.

* Return type: `list`

## <kbd>Setters:</kbd>
**FlightSeat** has total 6 setter properties.

### GoToCabinPosition
Navigate to a cabin position. Position can be 'Top', 'Middle', or 'Last'.

* Input type: `text`
* Helper type: `PositionType`
* Helper enums: `Top`, `Middle`, `Last`

### MaxSelectStates
Maximum number of seats that can be selected at once.

* Input type: `number`

### PlaneBackgroundColor
Set the background color of the plane area.

* Input type: `number`

### PlaneOutlineColor
Set the outline color of the plane body.

* Input type: `number`

### PlaneTailColor
Set the tail color of the plane.

* Input type: `number`

### PlaneCabinColor
Set the cabin color of the plane interior.

* Input type: `number`

## <kbd>Getter:</kbd>
**FlightSeat** has total 1 getter property.

### MaxSelectStates
Maximum number of seats that can be selected at once.

* Return type: `number`

