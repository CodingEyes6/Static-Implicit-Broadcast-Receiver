------------- Steps to Create Static/Implicit BroadCast Receiver----------------------



    step1. Create custom class and extend BroadCast Receiver

-- override onreceive


    step2: Go to manifest file 


     -- use receiver tag under applocation tag
     -- in receiver tag use intent-filter tag
     -- use action tag inside intent-filter tag
     -- in action tag give your action like android.intent.BOOT_COMPLETED
     -- add uses-permission for Boot completed outside application tag