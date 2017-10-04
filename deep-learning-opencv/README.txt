
$ python deep_learning_with_opencv.py --image images/jemma.png \
--prototxt bvlc_googlenet.prototxt \
--model bvlc_googlenet.caffemodel --labels synset_words.txt

$ python deep_learning_with_opencv.py --image images/traffic_light.png \
--prototxt bvlc_googlenet.prototxt \
--model bvlc_googlenet.caffemodel --labels synset_words.txt

$ python deep_learning_with_opencv.py --image images/eagle.png \
--prototxt bvlc_googlenet.prototxt \
--model bvlc_googlenet.caffemodel --labels synset_words.txt

$ python deep_learning_with_opencv.py --image images/vending_machine.png \
--prototxt bvlc_googlenet.prototxt \
--model bvlc_googlenet.caffemodel --labels synset_words.txt

$ FILES=images/*;
for f in $FILES; 
do python deep_learning_with_opencv.py --image $f --prototxt bvlc_googlenet.prototxt --model bvlc_googlenet.caffemodel --labels synset_words.txt;
done;
