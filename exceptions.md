## Documentation for exceptions

### **1.** HelperSMSException - Base exception
### **2.** NoApiKeyProvidedException - API key not passed
### **3.** BadApiKeyProvidedException - Invalid API key provided
### **4.** ForbiddenAccessException - User violated the access rules
##
### **5.** BadCountryIdException - Invalid country ID
### **6.** BadServiceIdException - Invalid service ID
### **7.** WrongOperatorCodeException - There is no operator with this code
### **8.** InternalErrorException - Server error
### **9.** NoNumbersException - No numbers
### **10.** BlockedUserException - User blocked
### **11.** InsufficientFundsException - No enough founds on the balance
### **12.** CannotBuyMailRuServicesException - User has not been verified for MailRU purchase
### **13.** NoNumbersWithMaxPriceException - A request to obtain numbers with a maximum price limitation cannot be fulfilled
### **14.** TooFastOperationException - Order status changes too often, need to wait for 1 second
### **15.** OrderStatusChangeException - If they try to cancel an order that has already received a code or has already been canceled/completed
### **16.** TooEarlyCancellationException - Canceling an order before a certain time has elapsed 
### **17.** OrderProcessingException - Error during finishing or canceling order
### **18.** UnsupportedOrderTypeException - The API currently covers all order types, but is left for the future if new order types become available
### **19.** TechnicalWorksException - Technical works
### **20.** RentTimeNotAvailableException - Not available with this rent_time
### **21.** InvalidServiceCountException -  Incorrect number of services

##

### **22** ValidationException - The data was transmitted in an incorrect format
### **23** OtherApiException - Made just in case