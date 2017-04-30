
git clone git@github.com:tonsV2/MyBiz2.git

cd MyBiz2/

git submodule update --recursive --remote

./mvnw spring-boot:run -Drun.profiles=test
