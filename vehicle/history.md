Example Request:

https://api.gpsinsight.com/v2/vehicle/history?session_token=xxxx&vehicle=CA4531009XXX&date=8/1/2015

Example Response:

    {
      head: { .... },
      data: [
        {
          id: "CA4531009XXX",
          vin: "5FNRL384878031XXX",
          label: "Truck 204",
          serial_number: 4531009036,
          age_minutes: 52322,
          timezone: "MST",
          fix_time: "7/15/15 07:18:08",
          fix_time_mst: "7/15/15 07:18:08 MST",
          fix_time_gmt: "2015-07-15T14:18:08+00:00",
          latitude: 33.65958,
          longitude: -111.92484,
          heading: 197,
          ignition: "off",
          max_speed: 40,
          avg_speed: 9,
          inst_speed: 5,
          speed_limit: 45,
          speed_label: "Stopped 36 days",
          speed_icon: "red_dot",
          odometer: 56844.6,
          driver_id: 45514XX,
          first_name: "Tom",
          last_name: "Gypsy"
        }, { ... }
      ]
    }
