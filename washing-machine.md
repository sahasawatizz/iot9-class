# Washing machine state

## START
topic:v1cdti/app/get/6420301001/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/6420301001/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6420301001/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Fill water"

}

## HEATWATER
topic:v1cdti/app/get/6420301001/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Heat water"
    
}

## WASH
topic:v1cdti/app/get/6420301001/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Wash"
    
}

## RINSE
topic:v1cdti/app/get/6420301001/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Complete"
    
}

## SPIN
topic:v1cdti/app/get/6420301001/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Spin"
    
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/set/6420301001/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Close"
    
}

## WATERFULLLEVEL
topic:v1cdti/app/set/6420301001/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Water Full"
    
}

## TEMPERATUREREACHED
topic:v1cdti/app/set/6420301001/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Temp reach"
    
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/set/6420301001/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Timeout"
    
}

## OUTOFBALANCE
topic:v1cdti/set/monitor/6420301001/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Balance"
    
}

## MOTORFAILURE
topic:v1cdti/app/set/6420301001/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Fail"
    
    
}

## FAULTCLEARED
topic:v1cdti/app/set/6420301001/model-01/sn-01
payload: {
    "action"    :   "set,
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Fault clear"
    
}
