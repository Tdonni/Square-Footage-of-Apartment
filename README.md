def calculate_rent(sqft, cost_per_sqft):
  """
  Calculates the rent for an apartment given its square footage and cost per square foot.

  Args:
    sqft: The square footage of the apartment.
    cost_per_sqft: The cost per square foot of the apartment.

  Returns:
    The calculated rent for the apartment.
  """
  return sqft * cost_per_sqft

if __name__ == "__main__":
  cost_per_sqft = float(input("Enter the cost per square foot: $")) 

  apt1_sqft = float(input("Enter the square footage of apartment 1: "))
  apt2_sqft = float(input("Enter the square footage of apartment 2: "))
  apt3_sqft = float(input("Enter the square footage of apartment 3: "))

  apt1_rent = calculate_rent(apt1_sqft, cost_per_sqft)
  apt2_rent = calculate_rent(apt2_sqft, cost_per_sqft)
  apt3_rent = calculate_rent(apt3_sqft, cost_per_sqft)

  print("\nApartment 1:")
  print(f" - Square Footage: {apt1_sqft} sq ft")
  print(f" - Rent: ${apt1_rent:.2f}")

  print("\nApartment 2:")
  print(f" - Square Footage: {apt2_sqft} sq ft")
  print(f" - Rent: ${apt2_rent:.2f}")

  print("\nApartment 3:")
  print(f" - Square Footage: {apt3_sqft} sq ft")
  print(f" - Rent: ${apt3_rent:.2f}")# Square-Footage-of-Apartment
Calculate the square footage cost on three apartment rentals to decide which is the least expensive. This is a program to calculate the square footage of three apartments, and how much it would cost to rent (based on the square footage). Ask how much per square feet in order to calculate the cost of renting. The final step is to show how much each apartment costs so I can compare them. 
