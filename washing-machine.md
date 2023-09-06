# Washing machine state

## START
topic:v1cdti/hw/set/6310301012/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Start"
}

## READY
topic:v1cdti/hw/get/6310301012/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Ready"
}

## FILLWATER
topic:v1cdti/hw/get/6310301012/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "Fill Water"
}

## HEATWATER
topic:v1cdti/hw/get/6310301012/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEATWATER"
}

## WASH
topic:v1cdti/hw/get/6310301012/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WASH"    
}

## RINSE
topic:v1cdti/hw/get/6310301012/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "RINSE"    
}

## SPIN
topic:v1cdti/hw/get/6310301012/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "SPIN"    
}

# Operation state

## DOORCLOSE
topic:v1cdti/hw/set/6310301012/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "DOORCLOSE",
    "value"     :   "0","1"    
}

## WATERFULLLEVEL
topic:v1cdti/hw/set/6310301012/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "WATERFULLLEVEL",
    "value"     :   "0","1"    
}

## TEMPERATUREREACHED
topic:v1cdti/hw/set/6310301012/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "TEMPERATUREREACHED",
    "value"     :   "35"    
}


# FAULT state

## TIMEOUT
topic:v1cdti/hw/get/6310301012/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault",
    "value"     :   "Time Out"    
}

## OUTOFBALANCE
topic:v1cdti/hw/set/6310301012/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault",
    "value"     :   "Out of balance"    
}

## MOTORFAILURE
topic:v1cdti/hw/set/6310301012/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault",
    "value"     :   "Motor failure"    
}

## FAULTCLEARED
topic:v1cdti/app/set/6310301012/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301012",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Fault",
    "value"     :   "FaultCleared"    
}