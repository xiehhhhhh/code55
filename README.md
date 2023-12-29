# code55
package main;

public class
Piano implements Instrument{
    @Override
    public void play(int index) throws NoThisSoundException{
        if (index>10){
            throw new NoThisSoundException("您播放的歌曲不存在");
        }
        System.out.println("你正在播放钢琴曲");
    }
}
 
