# kotlin-extensions

- inflate views

- --> fun ViewGroup.inflate(layout: Int, attachToRoot: Boolean = false): View {
    return LayoutInflater.from(context).inflate(layout, this, attachToRoot)
}

- toast with default parameters
- --> fun showToast(applicationContext, message: String , duration : Int= Toast.LENGTH_SHORT){
         Context.Toast.makeText(applicationContext,message ,duration).show()  
     }
