
git clone git@github.com:tonsV2/MyBiz2.git
cd MyBiz2/
git submodule update --recursive --remote
cd mybiz-v2-business
./mvnw install
cd ../mybiz-v2-api
./mvnw spring-boot:run -Drun.profiles=test
