How do the following behave for large values of n? Give answers in big-O notation:  eg. O(n2)

a.
  for (int x=0; x<n; x++) {
    for (int y=n; y>0; y--) {
      data[x]  =  data[y]; 
    }
  }
--------------
|            |
--------------

b.
  for (int x=0; x<n; x++) {
    for (int y=1; y<n; y *= 2) {
      data[x]  =  data[y]; 
    }
  }
--------------
|            |
--------------

c.
  for (int x=0; x<n; x++) {
    data[x]  =  data[n-x];
  }
  for (int y=n; y>0; y /= 2) {
    data[y]  =  data[n-y];
  }
--------------
|            |
--------------
