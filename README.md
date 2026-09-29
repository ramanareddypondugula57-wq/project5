# project5
class GoodMorningThread extends Thread {
    public void run() {
        while (true) {
            System.out.println("Good Morning");
            try { Thread.sleep(1000); } catch (InterruptedException e) {}
        }
    }
}
class GoodMorningRunnable implements Runnable {
    public void run() {
        while (true) {
            System.out.println("Good Morning");
            try { Thread.sleep(1000); } catch (InterruptedException e) {}
        }
    }
}
