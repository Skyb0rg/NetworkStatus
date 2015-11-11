# NetworkStatus
get the iOS current network info(Swift)
# function
It used to examine the network's reachability and tell you which network type you are connecting(2/3/4G or WiFi)
# usage
let networkManeger = NetworkStatus()
let isNetworkAccess = networkManeger.isNetworkReachable()
let networkType = networkManeger.currentNetworkType()
let wifiName = networkManeger.getCurrentWifiInfo()
