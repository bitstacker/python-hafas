# libhbpublictransport
functions for parsing the Hafas public transport info system of VBN


## Usage

    from libhbpublictransport.libhbpublictransport import VPN
    v = VBN()
    print(v.getScheduleForStation(v.getStationId("Bremen, Hauptbahnhof")))

