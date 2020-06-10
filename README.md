#   q i m i n g x i n g - S q l i  
  
 #   q i m i n g x i n g   e x a m   S Q L   i n j e c t i o n   -   e n  
  
 # #   1 _ ) 	 a b o u t  
  
 ` ` `  
 Q i x i n g   e x a m i n a t i o n   s y s t e m   c a n   b e   u s e d   a s   a   n o n   r i g o r o u s   e x a m i n a t i o n   s y s t e m   i n   s c h o o l s   a n d   c o m p a n i e s .   I t   i s   e a s y   t o   g e n e r a t e   t e s t   p a p e r s   b y   a d d i n g   t e s t   q u e s t i o n s .   S y s t e m   f e a t u r e s   i n c l u d e :  
 ( 1 )   S u p p o r t   c o m p l e x   m a t h e m a t i c a l   f o r m u l a s .  
 ( 2 )   S u p p o r t   w o r d   t o   i m p o r t   t e s t   q u e s t i o n s .  
 ( 3 )   I t   s u p p o r t s   t e s t   p a p e r   c o p y i n g .   S t u d e n t   i n t r o d u c t i o n ,   e t c .  
 P l e a s e   u s e   t h e   s y s t e m   A S P . N E T   + M S S Q L   d e v e l o p m e n t   c a n   b e   u s e d   n o t   o n l y   a s   t h e   t e a c h i n g   o f   s c h o o l   t e a c h e r s ,   b u t   a l s o   a s   t h e   i n t e r n a l   s t a f f   t r a i n i n g   a n d   e x a m i n a t i o n   s y s t e m .  
 N o t e :   s o f t w a r e   r e q u i r e s .   N e t 4 . 5 . 1   o r   h i g h e r  
 D o w n l o a d   L i n k   h t t p : / / d o w n . c h i n a z . c o m / s o f t / 3 9 6 4 9 . h t m  
 ` ` `  
  
 # #     2 _ ) 	 V u l n e r a b i l i t y   a n a l y s i s  
  
 ` I n   t h e   c o d e ,   t h e   u s e r ' s   i n p u t   i s   n o t   f i l t e r e d   a n d   b r o u g h t   i n   d i r e c t l y `   * * S Q L * *   ` S t a t e m e n t ,   t h u s   f o r m i n g   a   S Q L   i n j e c t i o n   v u l n e r a b i l i t y . `  
  
 # #   3 _ ) 	 A n a l y s i s   p r o c e s s  
  
 B u i l d   l o c a l l y   a f t e r   d o w n l o a d i n g   s o u r c e   c o d e  
  
 F i r s t ,   u s e   d n s p y   t o   l o a d   t h e   * * D L L * *   u s e d   b y   a l l   p r o g r a m s �T h e n   c h e c k   t h e   s o u r c e   c o d e   o f   t h e   A S P X   f i l e   a n d   f i n d   t h e   m e t h o d   u s e d   i n   d n s p y  
  
 ! [ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 0 2 5 1 6 0 ] ( D : \ g i t \ q i m i n g x i n g \ R E A D M E . a s s e t s \ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 0 2 5 1 6 0 . p n g )  
  
 T h e   * * a c t i v e i d * * i n s i d e   t h e   r e d   b o x   i s   n o t   f i l t e r e d .   C o n s t r u c t   a   U R L   t o   t e s t ! [ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 1 5 7 4 8 0 ] ( D : \ g i t \ q i m i n g x i n g \ R E A D M E . a s s e t s \ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 1 5 7 4 8 0 . p n g )  
  
 ! [ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 2 0 4 4 4 7 ] ( D : \ g i t \ q i m i n g x i n g \ R E A D M E . a s s e t s \ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 2 0 4 4 4 7 . p n g )  
  
 E r r o r   r e p o r t e d   s u c c e s s f u l l y ,   * * i n c o m p l e t e   s i n g l e   q u o t a t i o n   m a r k * *  
  
 ! [ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 2 4 3 9 8 6 ] ( D : \ g i t \ q i m i n g x i n g \ R E A D M E . a s s e t s \ i m a g e - 2 0 2 0 0 6 1 0 1 1 0 2 4 3 9 8 6 . p n g )  
  
 p a y l o a d   ` h t t p : / / 1 9 2 . 1 6 8 . 7 1 . 1 7 0 / t e c h / p a g e s . a s p x ? a c t i v e i d = 1 + a n d + 1 = @ @ v e r s i o n - - `  
  
 # #   4 _ ) 	 R i s k   l e v e l  
  
 < f o n t   c o l o r = r e d > H i g h < / f o n t >  
  
 # #   5 _ ) 	 B u g   f i x  
  
 -   F i l t e r   u s e r   i n p u t  
  
 -   F o r c e   c o n v e r s i o n   o f   u s e r   i n p u t   o r   f o r m   v a l u e s 