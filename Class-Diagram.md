class User {
    id: INTEGER
    age: INTEGER
    name: String
    emailAddress: String
    DownloadApp()
    CreateNewAccount()
    Update()
    login()
    logout()
    RentScooter()
    ReturnScooter()
    PayForRental()
    ReportDamange()
}

class Scooter {
    id: INTEGER
    battetylevel: INTEGER
    location: INTEGER
    inuse: BOOLEAN
    Lock()
    Unlock()
    Charging()
    EndRide()
}

class ChargingStation {
    ConfirmScooterDropOff()
    FullyChargedScooterAvailability: ARRAY
    RemoveScooter()
    broken:ARRAY
}

class ScooterApp {
    Authenticate()
    User()
    Register()
    MaxRidingRage() 
    VerifyAge()
    SafetyReq()
}

class Maintanence {
    RepairRequired()
    UpdateAvailableScooter: ARRAY
    RemoveScooter()
    OutOfService()
}