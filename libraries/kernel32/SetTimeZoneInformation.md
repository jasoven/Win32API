
## Function name : SetTimeZoneInformation
Group: Time - Library: kernel32    
***  


#### The SetTimeZoneInformation function sets the current time-zone parameters. These parameters control translations from Coordinated Universal Time (UTC) to local time.
***  


## Code examples:
[Retrieving information specific to the current Time Zone](../../samples/sample_073.md)  

## Declaration:
```foxpro  
BOOL SetTimeZoneInformation(
  const TIME_ZONE_INFORMATION* lpTimeZoneInformation
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER SetTimeZoneInformation IN kernel32;
	STRING lpTimeZoneInformation  
```  
***  


## Parameters:
lpTimeZoneInformation 
[in] Pointer to a TIME_ZONE_INFORMATION structure that contains the time-zone parameters to set.   
***  


## Return value:
If the function succeeds, the return value is nonzero.  
***  
