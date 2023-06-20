go mod init github/mitzen/gomock

# had to use full path on windows #
mockgen -source=c:\work\go\gomock\person\male.go -destination=c:\work\go\gomock\mock\male_mock.go -package=mocks