# app3-Explict-event-

An multiscreen app created using kotlin in Android Studio
App-Displays the 4 coloumns where you should enter some text.
when you press enter you will be directed into another screen it will show a ("Message" and "text you entered")

Learning : Explict intent in Android studio using kotlin

        button.setOnClickListener {
            val orderplaced=et1.text.toString() + " " + et2.text.toString() + " " + et3.text.toString()+
             " " + et4.text.toString()

            intent= Intent(this,order::class.java)
            intent.putExtra(KEY, orderplaced)
            startActivity(intent)
        }
