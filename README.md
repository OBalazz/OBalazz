md beeware-tutorial
cd beeware-tutorial
py -m venv beeware-venv
beeware-venv\Scripts\activate

briefcase new
cd helloworld
briefcase dev

briefcase create android
briefcase build android
briefcase run android
