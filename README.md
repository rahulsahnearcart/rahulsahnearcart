import phonenumbers
from phonenumbers import carrier, geocoder, timezone

mobileNo=input("+917061367534")
mobileNo=phonenumbers.parse(+917061367534)
print(timezone.time_zones_for_number(+917061367534))
print(carrier.name_for_number(+917061367534,"en"))
print(geocoder.description_for_number(+917061367534,"en"))
print("Valid Mobile Number:",phonenumbers.is_valid_number(+917061367534))
print("Checking possibility of Number:",phonenumbers.is_possible_number(+917061367534))
