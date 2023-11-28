# mnc_identifier_face

```dart
import 'package:mnc_identifier_face/mnc_identifier_face.dart';
import 'package:mnc_identifier_face/model/liveness_detection_result_model.dart';

...

 Future<void> startDetection() async {
    try {
      LivenessDetectionResult livenessResult =
                      await MncIdentifierFace().startLivenessDetection();
      debugPrint("result is $livenessResult");
    } catch (e) {
      debugPrint('Something goes unexpected with error is $e');
    }
  }
```

## Bugs or Contributing

If you encounter any problems feel free to open an issue. If you feel the library is missing a feature, please raise a ticket. Pull request are also welcome.



