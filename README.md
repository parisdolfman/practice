class Place

  def initialize(city)
   @city = city
  end
  
  def city=(city)
   @city = city
  end
  
  def city
   @city
  end
end

party_city = Place.new("Paris")
puts party_city.city

class Where
  
  def initialize(country)
    @country = country
  end 
  
  def country=(country)
    @country = country
  end
  
  def country
    @country
  end
end

place = Where.new("France")
puts place.country
