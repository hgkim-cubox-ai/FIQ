# FIQ

모델 다운로드
mediapipe - face_landmarks.tflite
https://storage.googleapis.com/mediapipe-assets/face_landmark.tflite

모델 변환
python -m tf2onnx.convert --tflite tflite_path --output output_path