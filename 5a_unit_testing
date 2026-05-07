import unittest
from EmotionDetection.emotion_detection import emotion_detector


class TextEmotionDetector(unittest.TestCase):
    def test1(self):
        res1 = emotion_detector("I am glad this happened")
        self.assertEqual(res1, "joy")
        res2 = emotion_detector("I am really mad about this")
        self.assertEqual(res2, "anger")
        res3 = emotion_detector("I feel disgusted just hearing about this")
        self.assertEqual(res3, "disgust")
        res4 = emotion_detector("I am so sad about this")
        self.assertEqual(res4, "sadness")
        res5 = emotion_detector("I am really afraid that this will happen")
        self.assertEqual(res5, "fear")


unittest.main()
