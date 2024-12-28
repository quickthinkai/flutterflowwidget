# This is the code of file name is NewCustomWidget
# https://pub.dev/packages/simple_gradient_text/example
    // Automatic FlutterFlow imports
    import '/backend/schema/structs/index.dart';
    import '/backend/schema/enums/enums.dart';
    import '/flutter_flow/flutter_flow_theme.dart';
    import '/flutter_flow/flutter_flow_util.dart';
    import '/custom_code/widgets/index.dart'; // Imports other custom widgets
    import '/flutter_flow/custom_functions.dart'; // Imports custom functions
    import 'package:flutter/material.dart';
    // Begin custom widget code
    // DO NOT REMOVE OR MODIFY THE CODE ABOVE!

    //import '/backend/schema/structs/index.dart';

    //import '/backend/schema/structs/index.dart';

    import 'package:simple_gradient_text/simple_gradient_text.dart';

    class NewCustomWidget extends StatefulWidget {
      const NewCustomWidget({
        super.key,
        this.width,
        this.height,


#add this line

    
    this.text1,


    
      });

      final double? width;
      final double? height;



  
#add this line

      final String? text1;

      @override
      State<NewCustomWidget> createState() => _NewCustomWidgetState();
      }

      class _NewCustomWidgetState extends State<NewCustomWidget> {
      @override
      Widget build(BuildContext context) {
        return Container(



#add these line


          width: widget.width,
          height: widget.height,


#add this word     child:



          child: GradientText(


#add this line
         
          
          
          widget.text1!,
          
          style: TextStyle(
            fontSize: 40.0,
              ),
              colors: [
                Color.fromARGB(255, 7, 120, 213),
                const Color.fromARGB(255, 138, 10, 1),
                Color.fromARGB(255, 215, 1, 204),
                ],
                ));
                  }
                  }

# only one parameter is added
simple_gradient_text: ^1.2.3
