require 'jwt'

api_key = 'API_KEY' # Specify your API key
phtoken = 'your_jwt_token_here' # Replace with the JWT token you want to decode

jwt_response = 0
jwt_phone = ''

begin
  decoded = JWT.decode(phtoken, api_key, true, algorithm: 'HS256')[0]
  jwt_response = 1 # JWT decoded successfully
  jwt_phone = "#{decoded['country_code']}#{decoded['phone_no']}"
rescue JWT::ExpiredSignature
  jwt_response = 0 # Invalid JWT
rescue JWT::DecodeError
  jwt_response = 0 # Invalid JWT
end

puts "JWT Response: #{jwt_response}"
puts "JWT Phone: #{jwt_phone}"
