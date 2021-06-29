default:
	$(CXX) -std=c++17 -fsanitize=address TopicTree.cpp -o TopicTree
	./TopicTree
	$(CXX) -std=c++17 -fsanitize=address HttpRouter.cpp -o HttpRouter
	./HttpRouter
	$(CXX) -std=c++17 -fsanitize=address BloomFilter.cpp -o BloomFilter
	./BloomFilter
	$(CXX) -std=c++17 -fsanitize=address ExtensionsNegotiator.cpp -o ExtensionsNegotiator
	./ExtensionsNegotiator

.PHONY: commands
commands:
	rm -f commands.log
	echo $(CXX) -std=c++17 -fsanitize=address -c TopicTree.cpp >> commands.log
	echo $(CXX) -std=c++17 -fsanitize=address -c HttpRouter.cpp >> commands.log
	echo $(CXX) -std=c++17 -fsanitize=address -c BloomFilter.cpp >> commands.log
	echo $(CXX) -std=c++17 -fsanitize=address -c ExtensionsNegotiator.cpp >> commands.log
